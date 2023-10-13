<link rel="icon" href="favicon.ico" type="favicon.ico">

<img src="nomo-logo-square.jpg" width="400" height="90">

# Nomo App Developer Hub

In the beginning, the [Nomo App](https://nomo.app) was only a crypto wallet, but now the Nomo App has evolved into a "super app".
Thereby, the Nomo App provides a whole new platform for third-party developers to build new use cases on top of the Nomo App.
This site provides an overview for developers who want to build within the Nomo platform.

The Nomo App provides the following products for third-party developers:

- Nomo Plugins: Run anything you like within the Nomo App, including decentralized Apps ("_DApps_").
- Nomo-ID: A protocol for authenticating via the Nomo App.

## Nomo Plugins

A plugin is a **web application** that works within the Nomo App.
Plugins are a powerful capability of the Nomo App that unlock the following features in an easy-to-use way:

- Crypto wallet functionality.
- Decentralized messaging.
- Optional: Verification that users are real via a KYC mechanism.
- AI-powered features.
- Authentication with Nomo-ID or Nomo-Auth.
- And much more to come...

### Find out more about Nomo Plugins

Visit the **Nomo Plugin Kit** at the [GitHub repository](https://github.com/nomo-app/nomo-plugin-kit) to see what plugins can do.
The repository contains a demo plugin where you can see how to create a plugin for the Nomo app.

Moreover, the following npm packages are provided for plugin developers:

- <https://www.npmjs.com/package/nomo-plugin-kit>
- <https://www.npmjs.com/package/ethersjs-nomo-plugins>
- <https://www.npmjs.com/package/web3js-nomo-plugins>

## Nomo-ID

Nomo-ID is a flexible protocol for web3-based authentication, without any passwords.
There exist multiple websites that allow login via Nomo-ID, but Nomo-ID can do much more than logins.

You can find out more about Nomo-ID at the [GitHub repository](https://github.com/nomo-app/nomo-id).

### Nomo-ID Sample Application

The repository contains a specification of the protocol as well as a sample application.
The backend of the sample application is written in Node.js/Express, and the frontend is written in React/Next.js.

Although the sample application contains a frontend, the Nomo-ID protocol could be used even without any frontend.
In a minimal use case, Nomo-ID could be used just by printing a QR code on a piece of paper.
