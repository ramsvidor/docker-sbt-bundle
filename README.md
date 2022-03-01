# Debian based GraalVM Community Edition/Scala/sbt for Docker

Hands-on Docker image for Scala applications running on [GraalVM CE](https://www.graalvm.org) and [Debian](https://www.debian.org).

**@see** [Dockerfile](https://github.com/ramsvidor/docker-sbt-bundle/blob/develop/Dockerfile)

## Base image
* [Official Debian 11 (_bullseye_)](https://hub.docker.com/_/debian) - bullseye-slim variant.

## How to use this image
### Pull and start a Java instance
* `docker pull ramsvidor/sbt-bundle`
* `docker run --rm --name java ramsvidor/sbt-bundle java -version`
* `docker run --rm --name scala ramsvidor/sbt-bundle scala -version`

## Supported Docker versions
This image is officially supported on Docker version 20.10 and newer.
Support for older versions is provided on a best-effort basis.
Please see the [Docker installation documentation](https://docs.docker.com/install/) for details on how to upgrade your 
Docker daemon.

## Contributing
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull 
requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a 
[GitHub issue](https://github.com/ramsvidor/docker-sbt-bundle/issues), especially for more ambitious contributions. This 
gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you 
find out if someone else is working on the same thing.

## License
This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
