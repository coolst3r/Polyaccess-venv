# PolyAccess

<small>low-profile malware made in python</small>

***for educational purposes only***




**still under development**


Features:

```
>Remote Access through shell
>keglogging
>grab chrome passwords
>registry persistence
>upload and download files
>undetectable (almost)
>screenshot
>checkprivilege
>grab discord token(through webhook)
>screenshare
>checkporn
``` 

Update
```
>added checkporn feature which check the PC for visited porn websites using dns (able to send log through discordwebhook)
```

Upcoming features:
```
play sound in background
AES encryption tunneling
```

**How to use?**

```
1. edit the host and the port in the config.py



2. install the requirements.txt using "pip3 install -r requirements.txt"


3. and then "build" the backdoor.py using pyinstaller or nuitka (you can run the builder.py to build it with pyinstaller)
NOTE: if you are building on windows 11, windows 11 defender might detect and prevent the building process, so it is adviced that you stop windows defender, however the payload generated will still be undetectable



4. start the listener.py on your machine and execute the payload on the target machine
```

python to exe detection (nuitka):
![image](https://user-images.githubusercontent.com/93959737/218252308-fc080a70-c2df-401a-b6ff-99dac0bd9abe.png)


Evading Bitdefender example:

https://www.youtube.com/watch?v=iqlV4gZxqIw&t=2s




Discord server for enquiries:
https://discord.gg/3R3BaDrTPK
