# EasyToAirdrop

**A website that helps you quickly obtain airdrops**

website: https://www.easytoairdrop.com

## Env

1. Node 16.18
2. Python 3.12

```shell
pip install gyp-next
```

3.  

Windows:

- Visual Studio Installer: https://visualstudio.microsoft.com/

Mac:

- XCode -appstore



## Step

1. Make dir

```shell
mkdir data
```

2. touch file

```shell
touch data/api.txt
touch data/proxy.txt
```

3. install dependencies

```shell
npm i
```

4. start 

```shell
npm run start
```



## Required data



1. If your need proxy address, put address into data/proxy.txt like this

```txt
http://user:pass@ip:port
http://user:pass@ip:port
http://user:pass@ip:port
```

2. Add WebSite User Data

- go to https://www.easytoairdrop.com, sign in and login in

- hover the avator to export the user.json

- put the user.json to data/

3. Add QueryId
put the query_id.txt to data/[gamename]/

### More Info
look_at: [https://www.easytoairdrop.com](https://www.easytoairdrop.com/home/article-view?articleId=ART-925005709836&isPublished=true)
