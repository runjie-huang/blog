```
ps -ef | grep stress |cut -c 9-15 | xargs kill -9
```
>`ps -ef` find all process 
>`grep stress` find the process with string "stress"
>`cut -c 9-15` select the string with location from 9th to 15 th
>`xargs kill -9` kill the selected process
