# Consul Agent in Docker

This project is a Docker container for [Consul](http://www.consul.io/). It's a slightly opinionated, pre-configured Consul Agent made specifically to work in the Docker ecosystem.

See [progrium/consul](https://github.com/progrium/docker-consul) documentation. Changes are: 
* removed predefined recursor, you can add -recursor {IP} to set desired recursor on start.

