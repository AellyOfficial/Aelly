<p align="center">
  <img src="images/Aelly_Logo.png" height="400px"/>
</p>


# 💠[Aelly](https://myAelly.com/)💠
> Your Personal Assisstant, on WhatsApp!
---

Aelly is an optimized and easy-to-use WhatsApp UserBot written in Node.js.
Utilize your personal chat assistant/group manager to make the most out of WhatsApp.   






## Deployment

<b>Only local deployment is working for now!</b>

### Manually on Heroku

<b>Deployment to heroku using the button is not working for now!</b>

You can deploy the bot the heroku yourself using the button below!

## ㅤㅤㅤᴅᴇᴘʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ​ 🚀
ㅤㅤㅤᴛʜᴇ ᴇᴀsɪᴇsᴛ ᴡᴀʏ ᴛᴏ ᴅᴇᴘʟᴏʏ Aelly
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/anunicn47/Aelly"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

### Using Docker locally

To follow this method, you will need to have docker installed on your machine and have some experience using docker.

To host the bot on your own device using docker, follow the following steps on your terminal / command prompt -

```bash
wget -O Aelly.tar.gz https://github.com/AellyOfficial/Aelly/archive/refs/tags/v2.0.0-beta.tar.gz
tar -xvzf Aelly.tar.gz
cd Aelly-2.0.0-beta
docker build -t Aelly .
docker run --rm --name Aelly Aelly
```

This will create a container running Aelly. You'll have to scan the QR at least once.

### The GNU/Linux Legacy Way

To use this method, you will need ffmpeg, nodejs, npm installed on your device.

To run the bot on your device manually, you can use the following commands -

```bash
git clone https://github.com/AellyOfficial/Aelly.git
cd Aelly
yarn
npm start
```

## Scan QR Code again
If you're having issues when running locally it is recommended to scan the code again. To get the QR code again, follow these commands -
```
rm -rf Aelly.db session.data.json
npm start
```

## Support and Discussion groups

Feel free to post your queries or concerns on any of the discussion forums mentioned below:

[![Join Telegram Group](https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=Telegram)](https://t.me/itz.AellyRbot)

## Inspiration

- Baileys Library

- Yusuf Usta 

- [X-tra-Telegram](https://github.com/Prince-Mendiratta/X-tra-Telegram)

## Copyright & License
- Copyright (C) 2021 - 2022 by [AellyOfficial](https://github.com/AellyOfficial)

- Licensed under the terms by [GNU GENERAL PUBLIC LICENSE](https://github.com/AellyOfficial/Aelly/blob/main/LICENSE)

## Legal
This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by WhatsApp or any of its affiliates or subsidiaries. This is an independent and unofficial software. Use at your own risk.
