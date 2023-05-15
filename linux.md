## Check running port on linux
https://www.cyberciti.biz/faq/unix-linux-check-if-port-is-in-use-command/
```shell
sudo lsof -i -P -n | grep LISTEN
```
## kill a process running on particular port in Linux
https://stackoverflow.com/questions/11583562/how-to-kill-a-process-running-on-particular-port-in-linux
```shell
sudo kill -9 $(lsof -t -i:8080)
```
