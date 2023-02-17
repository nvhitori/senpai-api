
![senpai-api](https://telegra.ph/file/77f5707606b04dda26e01.jpg)
# SENP4I - API's
<p align="center">
<a href="https://github.com/nvsenpai/senpai-api/network/members" alt="GitHub stars"> <img src="https://img.shields.io/github/stars/nvsenpai/senpai-api?style=flat&logo=github&color=yellow" /> </a>
<a href="https://github.com/nvsenpai/senpai-api/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/nvsenpai/senpai-api" /> </a>
</p>
<p align="center">
<a href="https://github.com/nvsenpai/senpai-api" alt="GitHub commit activity"> <img src="https://img.shields.io/github/commit-activity/m/nvsenpai/senpai-api" /> </a>
<a href="https://github.com/nvsenpai/senpai-api/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/nvsenpai/senpai-api?style=flat&logo=github" /> </a>
<a href="https://github.com/nvsenpai/senpai-api" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/nvsenpai/senpai-api?color=success" /> </a>
<a href="https://github.com/nvsenpai/senpai-api" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/nvsenpai/senpai-api?style=flat&logo=github&color=red" /> </a>
<a href="https://github.com/nvsenpai/senpai-api" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/nvsenpai/senpai-api?style=flat&logo=github&color=success" /> </a>
</p>
<p align="center">
<a href="https://github.com/nvsenpai/senpai-api" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/nvsenpai/senpai-api" /> </a>
<a href="https://github.com/nvsenpai/senpai-api/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/github/license/nvsenpai/senpai-api?style=flat&logo=github&color=success" /> </a>
</p>
<p align="center">
<a href="" alt="nvsenpai"> <img src="https://img.shields.io/badge/built%20by-nvsenpai-blue" /> </a>
<a href="https://github.com/nvsenpai/senpai-api/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/maintained%3F-yes-blue.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-blue.svg" /> </a>
</p>

![Alt](https://repobeats.axiom.co/api/embed/994be5af506efd008b9ac5aa95c76a4472798a25.svg "Repobeats analytics image")

### Required

Sebelum melakukan apapun silahkan dapatkan
* [Mongo DB URI](https://www.mongodb.com)

Tanpa mongodb web API tidak akan berjalan

buat file .env terlebih dahulu
```shell
mv example.env .env
```
letakkan semua itu di file .env

```javascript
DB_URI = '' //URI Database mongodb bisa kalian dapatkan di https://www.mogodb.com
LIMIT_PREMIUM =  ''//Limit pengguna gratisan
LIMIT_USER = '' //Limit pengguna premium
CODER_NAME = '' //Entahlah mau di ganti apa tidak
KEY = '' //Kata kunci untuk menambahkan pengguna premium
```

## Linux

```shell
apt update -y
apt upgrade -y
apt install nodejs -y
apt install npm -y
apt install git -y
```

### Runing in localhost

```shell
npm install --global nodemon
git clone https://github.com/nvsenpai/senpai-api
cd senpai-api
npm install
npm start
```
Open : [http://localhost:8080](http://localhost:8080)
### Deploy in heroku

```shell
npm install --global heroku
heroku login
git clone https://github.com/nvsenpai/senpai-api
cd senpai-api
hroku git:remote -a YOUR_APP_NAME_IN_HEROKU
git add .
git commit -m "Make It Butter"
git push heroku master
```

#### Or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/nvsenpai/senpai-api)

Open : [https://APP_NAME.herokuapp.com](https://APP_NAME.herokuapp.com)
Demo : [https://apisenpai.vercel.app](https://april-api.herokuapp.com)
## What is next?

* Jika masih bingung silahkan tanyakan kepada saya di [WhatsApp](https://chat.whatsapp.com/JmI2yMIC2LFD5Mig8eoNkx)
* Menemukan error? silahkan tarik permintaan, atau bisa beritahu saya di [WhatsApp](https://chat.whatsapp.com/JmI2yMIC2LFD5Mig8eoNkx)
* Request? silahkan hubungi saya di [WhatsApp](https://chat.whatsapp.com/JmI2yMIC2LFD5Mig8eoNkx)
* [lolkil-scraper](https://npmjs.com/package/lolkil-scraper)

<div align="center">
  <h2>All Contributors !</h2>

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/LoliKillers"><img src="https://avatars.githubusercontent.com/u/80396688?v=4?s=100" width="100px;" alt="Lolii Kilers"/><br /><sub><b>Lolii Kilers</b></sub></a><br /><a href="https://github.com/nvsenpai/senpai-api/commits?author=LoliKilers" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/nvsenpai"><img src="https://avatars.githubusercontent.com/u/53950128?v=4?s=100" width="100px;" alt="V4LL"/><br /><sub><b>V4LL</b></sub></a><br /><a href="https://github.com/nvsenpai/senpai-api/commits?author=nvsenpai" title="Code">💻</a> <a href="#ideas-nvsenpai" title="Ideas, Planning, & Feedback">🤔</a></td>

