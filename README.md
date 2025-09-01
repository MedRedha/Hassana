<p align="center"> <img src="./bismillah.svg" alt="Hassana App Logo" width="500"/> </p>

<h1 align="center">
  My Hassana - Alexa Skill
</h1>

<p align="center"> 
  Your daily companion for Islamic prayer times, right on your Alexa device
</p>

<p align="center">
  <img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/MedRedha/Hassana?filename=lambda/package.json&style=flat&color=blueviolet&label=Version&logo=devbox">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/MedRedha/Hassana?logo=dailydotdev&color=red">
  <img alt="GitHub License" src="https://img.shields.io/github/license/MedRedha/Hassana?&logo=openaccess">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/t/MedRedha/Hassana?logo=git">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/MedRedha/Hassana?style=flat&logo=polestar&color=gold">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/MedRedha/Hassana">
  
</p>

<p align="center"> 
  <a href="[https://www.amazon.com/alexa-skills](https://www.amazon.com/alexa-skills)" title="Available on Alexa"> 
    <img src="https://static.wikia.nocookie.net/logopedia/images/8/86/Just_Ask_Alexa_2017_%28Badge_II%29.svg" alt="Available on Alexa Badge" width="100"/> 
  </a> 
</p>

----------

## 📖 Table of Contents

- [📖 About The Project](#-about-the-project)
- [🚀 Features](#-features)
- [🗣️ Usage](#%EF%B8%8F-usage)
- [🛠️ Built With](#%EF%B8%8F-built-with)
- [👨‍💻 Development & Setup](#-development--setup)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

----------

## 📖 About The Project

In the name of **Allah**, the Most Gracious, the Most Merciful.

This project was born from a simple, heartfelt need. My wife, (_may Allah bless her_), as we live in a
country
with few
mosques, and she deeply missed hearing the beautiful call to prayer (_the Adhan_) five times a day.

Inspired by this, and seeking only the pleasure of Allah (_سبحانه وتعالى_), I developed Hassana (_حسنة_). My intention
is for this
work to be purely for His sake (_lillāh_), as a tool to help fellow Muslims connect with their daily prayers. It is for
this reason that the skill is, and insha'Allah (_God willing_) will always remain, completely free for everyone.

Hassana serves as your personal muezzin, integrating with the reliable AlAdhan API to:

- Provide accurate Islamic prayer times for any city on demand.
- Deliver beautiful, automated Adhan notifications at the time of each prayer.

This Alexa Skill is the first humble step in a larger project that will eventually include native iOS and Android
applications, insha'Allah.

## 🚀 Features

- **Daily Prayer Times**: Get the timings for _Fajr_, _Dhuhr_, _Asr_, _Maghrib_, and _Isha_ for any city in the world.
- **Adhan Notifications**: Receive automated notifications for each prayer time. (can be adjusted in the settings).
- **Specific Prayer Time**: Ask for the time of a single, specific prayer.
- **Voice-First Design**: Built from the ground up for a seamless voice interaction experience.
- **Accurate Data**: Powered by the reliable and widely-used [AlAdhan API](https://aladhan.com/prayer-times-api).

## 🗣️ Usage

#### Invocation Name

To start the skill, simply say:

> Alexa, open (launch/start/run) My Hassana

#### Example Phrases

Once the skill is open, you can ask things like:

> What are the prayer times for Algiers?

> Prayer times in London

> When is Maghrib in Paris?

## 🛠️ Built With

This project is powered by a modern, serverless stack:

- **Language**: [Node.js v24](https://nodejs.org/)

- **Framework**: [Alexa Skill Kit (ASK) SDK v2](https://developer.amazon.com/en-US/docs/alexa/alexa-skills-kit-sdk-for-nodejs/overview.html)

- **API**: [AlAdhan API](https://aladhan.com/prayer-times-api)

- **Hosting**: [AWS Lambda](https://aws.amazon.com/)

- **Infrastructure**: [AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/)

## 👨‍💻 Development & Setup

This skill is managed locally using the ASK CLI. Follow these steps to get started.

#### Prerequisites

- Node.js and npm

- An [Amazon Developer Account](https://developer.amazon.com/) and an [AWS Account](https://aws.amazon.com/)

- ASK CLI installed globally:

  ```
  npm install -g ask-cli
  
  ```

- Fork the repository and enjoy!

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any
contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please feel free to fork the repo and create a pull request, or
simply open an issue with the tag `enhancement`.

1. Fork the Project (`https://github.com/MedRedha/Hassana`)

2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)

3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)

4. Push to the Branch (`git push origin feature/AmazingFeature`)

5. Open a Pull Request (`https://github.com/MedRedha/Hassana/pulls`)

You can also raise an issue directly on
the [Issues page](https://github.com/MedRedha/Hassana/issues), and I will do my best to
respond quickly.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<h3 align="center">
  <b>
  Made with ❤️ by
    <a href="https://wuud-team.com/">
      Mohamed Redha Khelifi
    </a>
  </b>
</h3>
