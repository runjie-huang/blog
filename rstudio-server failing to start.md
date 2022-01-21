##This command to check rstudio server
```
rstudio-server failing to start
```
![image](https://user-images.githubusercontent.com/88473583/150475524-5169a7c5-fc5b-4007-b2ba-40619a28087e.png)

##The reason why you can not restart rstudio-server is that the PORT 8787 was been using by previous rserver. After knowing this, the solution is easy. First, check the pid that was using PORT 8787
```
sudo netstat -anp | grep 8787
```
![image](https://user-images.githubusercontent.com/88473583/150475846-4dbdb59c-3bad-4b27-b214-2183cfe6936f.png)

```
sudo kill -9 41018
```

```
sudo rstudio-server restart
```
