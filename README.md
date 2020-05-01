# 👋Covidhelper

A Flutter app to help to understand covid-19 with live global and local states and A smart SOS feature with local indian helpline number

<p align="center">
  <a href="https://www.paypal.me/gamitics">
    <img src="https://img.shields.io/badge/Donate-PayPal-blue.svg?style=for-the-badge">
  </a>

</p>

![GitHub issues](https://img.shields.io/github/issues-raw/spielers/covidhelper)
![GitHub](https://img.shields.io/github/license/spielers/covidhelper)
![GitHub followers](https://img.shields.io/github/followers/spielers?label=FOLLOW&style=social)


## Motivation

Unpresedented attack of the virus Covid-19 has hit worse on both small scale as well as large scale industries. Service providing companies got crushed down. And now when it is clear that the virus will have deepest possible impact on the world economy, many of the states will be interdependent for growth and support.
Corona outbroke in last week of december at Wuhan. 

this gave me an idea about creating a live support and stat showing application for normal peoples who are suffering from this massive outbreak.

## Installation

1]download or fork this repo

2]extract the zip by usig any extractor

3]Make sure to have npm and NodeJS installed. You may want to remove package-lock.json. Then install all dependencies by running this command.

4]open this folder by using vs code.

5]open terminal and type

```
npm i
```

### Developing

Use npm or yarn to start the development server.

npm:

```
npm run serve
```

yarn:

```
yarn serve
```

### Codebase

The main Vue app is located src/Views/App.vue. This contains the code for displaying the header, chat screen (fulfillment text, list select cards, etc.), and chat input. It also contains the code for sending user requests to the Gateway and fetching responses.

src/Components contains Vue components used in this app. You can edit the style of each component within each vue file contained in the Components folder.

To make changes to the theme, go to src/Style.

The Dialogflow agent url is included as an endpoint in src/Config/index.js. 

## API Reference

The Dialogflow agent.

## 🤝 Contribute

feel free to fork this repoistory.
Add your own features and send PR.

## Credits

@spielers.

