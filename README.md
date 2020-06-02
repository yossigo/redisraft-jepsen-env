Jepsen envs
===========

This repository hosts tooling to make it easy to run RedisRaft Jepsen tests:

* **docker** contains a Docker Compose setup that can run the entire test on a
  single compose environment.
* **aws** contains a Terraform script that makes it possible to run Jepsen on
  real AWS instances.
