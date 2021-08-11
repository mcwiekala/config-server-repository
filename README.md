## General info
This is a config repository for Cloud Config Server in [this project](https://github.com/mcwiekala/microservices). 

It's server side externalized configuration for distributed system. This configs are defined only for **LOCAL** development.
 
For demonstration purposes it is public (normally it should be private). So there is no any login or password to protect access. However passwords in configurations are encrypted using JCE.

Each `/yml` file is provided to different application. It's defined in: 

**config-server** app -> `bootstrap.yml` -> `spring.profiles`

To read the changes you have to commit and push the changes in repository defined in: `spring.cloud.config.server.git.uri` default branch is `master` 