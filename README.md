# ChadServ
A little asynchronous chatroom server that is compatible with clients like netcat

## Usage
```console
usage: chadserv [-h] ip port

Simple chat server for chads.

positional arguments:
  ip          server ip
  port        server port

options:
  -h, --help  show this help message and exit

```

## Server commands
```console
Server commands:
  help                          - display this text
  shutdown                      - shutdown the server
  online                        - list users that are online
  banned                        - list users that are banned
  kick  <user1> <user2> <userN> - kick N users
  ban   <user1> <user2> <userN> - ban N users
  unban <user1> <user2> <userN> - unban N users
```

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
