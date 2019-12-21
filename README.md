# My Docker Environment Configuration</br>[![maintained]][0]

This is my personal [Docker][1] environment configuration.</br>
It will probably won't work for you as-is,</br>
but you can of course tweak it to suite your needs.


You can also check out my [Home Assistant][2] configuration and [AppDaemon][3] configuration.

I'm running a **Hybrid Swarm** consist of the following nodes:

| Node Name        | Role      | Docker version | Arch     | OS                    |
| ---------------- | --------- | -------------- | -------- | --------------------- |
| `docker_station` | `Manager` | `19.03.5`      | `x86_64` | `Ubuntu 18.04.2`      |
| `haserver`       | `Worker`  | `19.03.5`      | `armv71` | `Raspbian buster 10 ` |
| `docker-desktop` | `Worker`  | `19.03.5`      | `x86_64` | `Windows 10 Pro`      |

> My Swarm is running behind an `Nginx Reverse Proxy`,</br>
> The ports published in my configuration are internal.

<!-- real links -->
[0]: https://github.com/TomerFi/my_docker_environment_configuration
[1]: https://www.docker.com/
[2]: https://github.com/TomerFi/my_home_assistant_configuration
[3]: https://github.com/TomerFi/my_appdaemon_configuration

<!-- badge links -->
[maintained]: https://img.shields.io/badge/maintained%3F-yes-green.svg
