## STORAGE Example Using Disk & Memory in Node.js

#### GET Requests

curl localhost:4444/memory/:key

curl localhost:4444/disk/:key

---
#### POST Requests

curl --header 'content-type: application/json' localhost:4444/memory/:key --data '{ "data": "CodezUp : Code The Way Up" }'

curl --header 'content-type: application/json' localhost:4444/disk/:key --data '{ "data": "CodezUp : Code The Way Up" }'
