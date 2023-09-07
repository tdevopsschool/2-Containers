moved to https://gitlab.com/t-systems-devops-school/2-Containers

## Homework 1
*[#homework]() [#containers1]()*
1. Create a volume in Docker
2. Run any 2 containers (e.g [tomcat:latest](https://hub.docker.com/_/tomcat)) and attached the volume to the first container in RO mode and to the second in RW mode
3. Do `docker inspect` for containers and send screenshots with RO/RW mode of the attached volume in the chat. Remember about homework hashtags

## Links 1
- [Docker Volume create](https://docs.docker.com/engine/reference/commandline/volume_create/)

## Homework 2
*[#homework]() [#containers2]()*
1. Create 2 Dockerfiles to containerize [backend and frontend](https://github.com/tdevopsschool/course-project)
2. Create **docker-compose.yml** and include these 2 containerized application plus postgeaql image for deploymet of DB for backend
3. Run `docker-compose` to build images and deploy
4. Check that course project is up and running
5. Send screenhost of **docker-compose.yml** file in the chat with homework hashtags

## Links 2
- [Docker compose](https://docs.docker.com/compose/)
- [Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
- [Using Docker-in-Docker for your CI or testing environment? Think twice](http://jpetazzo.github.io/2015/09/03/do-not-use-docker-in-docker-for-ci/)

## General useful links
- [Docker cheat sheet](https://github.com/eon01/DockerCheatSheet/blob/master/README.md)
- [Java inside Docker](https://developers.redhat.com/blog/2017/03/14/java-inside-docker)
- [Entrypoint vs CMD](http://www.johnzaccone.io/entrypoint-vs-cmd-back-to-basics/)
- [The Missing Introduction To Containerization](https://faun.pub/the-missing-introduction-to-containerization-de1fbb73efc5)
- [Learn to build and deploy your distributed applications easily to the cloud with Docker](https://docker-curriculum.com/)
- [You Don’t Have to Use Docker Anymore](https://towardsdatascience.com/its-time-to-say-goodbye-to-docker-5cfec8eff833)
- [Dockerfile linter, validate inline bash, written in Haskell](https://github.com/hadolint/hadolint)
- [Secure Your Containers with this One Weird Trick](https://www.redhat.com/en/blog/secure-your-containers-one-weird-trick)
- [Why top and free inside containers don't show the correct container memory](https://ops.tips/blog/why-top-inside-container-wrong-memory/)
- [7 Docker Tips](https://faun.pub/7-docker-tips-913b6f76ac8f)
