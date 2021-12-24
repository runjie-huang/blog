# how to download file by command line in window OS
1. open *cmd* pattern in window OS 
2. input the code
```
start powershell
```
3. 
```
$client = new-object System.Net.WebClient

$client.DownloadFile('#1', '#2')
```
* #1 is the download link \n
* #2 the path to storte in your computer (including the file name)
* eg.
```
$client = new-object System.Net.WebClient
$client.DownloadFile('http://202.116.105.10/singlecell_data.txt', 'D:\personal data\博士\一年级\课程\生物信息学\homework\text.txt')
```
see more <https://jingyan.baidu.com/article/9faa72318f7ea3473c28cbff.html>
