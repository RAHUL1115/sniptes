## Check running port on linux
https://www.cyberciti.biz/faq/unix-linux-check-if-port-is-in-use-command/
```shell
sudo lsof -i -P -n | grep LISTEN
```
