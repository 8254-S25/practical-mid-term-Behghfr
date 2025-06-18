I moved my MT25 file to here:

**1.**

```
scp E:\2ndLocal\BehzadGhafoury.txt pi@192.168.2.56:/home/pi
```


**2. 
```
ls -l
or with apath:
ls -l /home/pi
```


**3.**

```
ls -l > pr1.txt
```

**4.
```
-rw-r--r--
owner: read and write
group: read
others: read
```

**5. 
```
pwd
```


**6.**

```
chmod g=rx pr1.txt

```


**7.**

```
mkdir midtermExam-301
```

**8.**

```
drwxr-xr-x
owner: read and write and execute
group: read and wxcute
others: read and excute

```

**9.**

```
netstat -at
```


**10.**

```
netstat -at > pr2.txt
```



**11.**

```
 sftp pi@192.168.2.56
```


**12.**

```
put E:\2ndLocal\midtermPi.txt
```
```
**13.** What does the command do?

```
pwd > mt.txt :
saves the path that we are working in to a txt file named mt.txt
tree -l>>pr.txt:
it append the folder tree structure to the file pr.txt
```


**14.**

```
sudo useradd BehzadGhafoury
```



 **15.**


sudo mkdir /home/BehzadGhafoury
sudo chown BehzadGhafoury:BehzadGhafoury /home/BehzadGhafoury

```

**16.**

```
sudo apt-get update
sudo apt-get install filezilla -y

```



