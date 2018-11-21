# ZIMUZU WEBUI dockerfile
---

##Reference

[ZIMUZU offical](http://app.zimuzu.tv/)

##Quick start

```code

 docker run -d -p 3001:3001 --name=zimuzu  testimg
```

##Folder mapping


| Path | Description |
| --- | --- |
| /home/video/ | video download folder |
| /home/app/ | application root |
| /home/app/log/  | log folder |
| /home/app/rrshareweb/ | rrshareweb folder |
| /home/app/rrshareweb/conf/ | rrshareweb config folder |

```

docker run -d -p 3001:3001 -v /video/:/home/video/ --name=zimuzu  testimg
```


