# dgraph-docker-compose

🐳 + ⚡️: Docker-compose for starting dgraph-zero, dgraph-server and dgraph-rapel

## Usage

- Start the composed images with: `docker-compose up -d`.
  - It starts `dgraph-zero`, `dgraph-server` and `dgraph-rapel`. Reference [here](https://docs.dgraph.io/get-started/#dgraph).

- Get logs with: `docker-compose logs`.

- For using `dgraph-rapel` (dgraph's UI), visit [localhost:8000](http://localhost:8000).
