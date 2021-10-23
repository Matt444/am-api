Install json-server:
npm i -g json-server

Then run server:
json-server db.json --watch

Get timers by: GET http://localhost:3000/timers/1

Modify by: PUT http://localhost:3000/timers/1 with body { "timestamp": 32523523 }
