# MongoDB

MongoDB 2.4.5

Uses `mongod` as the entrypoint with a default option of `--rest`

* `docker build -t mongodb .`
* `docker run mongodb -h` for all mongod options
* `docker run mongodb` for defaults

Ports

* 27017 (mongo)
* 28017 (mongo admin)
