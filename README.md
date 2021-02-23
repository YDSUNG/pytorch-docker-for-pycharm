# pytorch-docker-for-pycharm
This is pytorch docker repo for pycharm


## build docker container

```
docker build -t pytorch-for-pycharm .
```

## modifiy docker compose file


## pycharm setting 
### docker setting
- open pycharm
- move Preference > Build, Execution, Deploy

![pycharm-docker-settings](.img/20210223_092604.jpg){: width="100" height="100"}


### Python Interpreter setting
- add new interpreter

![interpreter-setting1](.img/20210223_093705.jpg){: width="100" height="100"}


- configure docker-compose
![interpreter-setting2](.img/20210223_104857.jpg){: width="100" height="100"}
