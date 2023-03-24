
### You must use Python version 3.7.9.

# WKS-KEY-Services 
An addon for WKS-KEY

> **Warning**
>
> I don't plan to update this at all, I'm only uploading this for educational, and archival purposes.

This is the original version of the script that a few others are based on.

## setup

usage: main.pyc {service} [-h]

### Example
> **ViX** 


> **https://vix.com/**

  - python main.pyc vix -mpd mpd_url -eqp eqp_license
  
![image](https://media.discordapp.net/attachments/707689574226460683/1088079900310782032/image.png)

You can find the eqp in the license

![image](https://media.discordapp.net/attachments/826590534151700550/1088085289181913118/image.png)


> **JFFP** 


> **https://watch.jff.jpf.go.jp/**

  - python main.pyc jffp -mpd mpd_url -t token
  
![image](https://media.discordapp.net/attachments/916452106523775036/1088114321608949770/image.png)

You can find the token in the license

![image](https://media.discordapp.net/attachments/826590534151700550/1088115982553337867/image.png)

> **DSNP** 

> **https://www.disneyplus.com/**
> **https://www.starplus.com/**

  - python main.pyc dsnp -pssh pssh_m3u8 -t token
  
![image](https://media.discordapp.net/attachments/916452106523775036/1088120876853121094/image.png)

You can find the token in the license

![image](https://media.discordapp.net/attachments/826590534151700550/1088135318370271343/image.png)

You can find the pssh in the m3u8

![image](https://media.discordapp.net/attachments/826590534151700550/1088135613573771305/image.png)

> **PMTP** 

> **https://www.paramountplus.com/**

  - python main.pyc paramountplus -pssh pssh_mpd -t token -id id
  
![image](https://media.discordapp.net/attachments/826590534151700550/1088872570314563665/image.png)

You can find the token in the license

![image](https://media.discordapp.net/attachments/826590534151700550/1088873557385293834/image.png)

You can find the id in the url "paramountplus.com/xxxx/xxxx/{id}/"

