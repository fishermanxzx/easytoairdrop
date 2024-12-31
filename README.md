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

1. Get TG Developer API KEY

- Log in to your Telegram core: https://my.telegram.org.

- Go to "API development tools" and fill out the form.

You will get basic addresses as well as the api_id and api_hash parameters required for user authorization.

- Put data into data/api.txt like this

```txt
apiId = 265***3
apiHash = 7c***90
```

2. If your need proxy address, put address into data/proxy.txt like this

```txt
http://user:pass@ip:port
http://user:pass@ip:port
http://user:pass@ip:port
```

3. Add WebSite User Data

- go to https://www.easytoairdrop.com,sign in and login in

- hover the avator to export the user.json

- put the user.json to data/

