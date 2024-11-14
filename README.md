<link rel="icon" href="favicon.ico" type="favicon.ico">

<img src="nomo-logo-square.jpg" width="400" height="90">

# Nomo App Developer Docs

In the beginning, the [Nomo App](https://nomo.app) was only a crypto wallet, but now the Nomo App offers a huge range of web3-features.
To enable those web3-features, the Nomo App uses the following open-source packages:

- WebOns: Decentralized Apps ("_dApps_") are running within the Nomo-WebView.
- WalletKit-Dart: A library for interacting with multiple chains.
- Nomo-UI-Kit: A collection of Flutter-widgets with Nomo design.
- Nomo-ID: A protocol for authenticating via the Nomo App.

## WebOns

See on GitHub: <https://github.com/nomo-app/nomo-webon-kit>

A WebOn is a **web application** that works within the Nomo App.
WebOns are a powerful capability of the Nomo App that unlock the following features in an easy-to-use way:

- Excellent user experience for web3: No more "Connect wallet" buttons; no more middlemans between web application and wallet.
- Decentralized messaging.
- Optional: Verification that users are real via a KYC mechanism.
- Authentication with Nomo-ID or Nomo-Auth.
- And much more to come...

The Nomo-WebOn-Kit provides a Demo-WebOn to showcase functionality.
Moreover, Nomo provides the following npm packages for WebOn developers:

- <https://www.npmjs.com/package/nomo-webon-kit>
- <https://www.npmjs.com/package/ethersjs-nomo-webons>
- <https://www.npmjs.com/package/nomo-webon-cli>
- <https://www.npmjs.com/package/nomo-messenger-kit>
- <https://www.npmjs.com/package/nomo-auth>

## WalletKit-Dart

See on GitHub: <https://github.com/nomo-app/walletkit-dart>

The WalletKit-Dart is an advanced library that provides wallet functionality for multiple chains.
The WalletKit-Dart supports both UTXO-chains and EVM-chains, including features like xPub/zPub/P2SH/SegWit.

### Nomo BIP39

See on GitHub: <https://github.com/nomo-app/bip39>

To protect Nomo users, the Nomo team maintains its own fork of BIP39 with additional security hardenings.
The WalletKit-Dart depends on Nomo BIP39.

## Nomo-UI-Kit

See on GitHub: <https://github.com/nomo-app/nomo-ui-kit>

Nomo-UI-Kit offers a collection of reusable widgets, such as buttons and cards.
Nomo-UI-Kit is designed for both the Nomo App itself as well as WebOns that are built with Flutter-Web.

## Nomo-WebView

See on GitHub: <https://github.com/nomo-app/nomo-webview>

Nomo-WebView allows to convert between JavaScript-Promises and Dart-Futures, such that async/await works seamless across language boundaries.

## Nomo-ID

See on GitHub: <https://github.com/nomo-app/nomo-id>

Nomo-ID is a flexible protocol for web3-based authentication, without any passwords.
There exist multiple websites that allow login via Nomo-ID, but Nomo-ID can do much more than logins.
The Nomo-ID repo contains a specification of the protocol as well as a sample application.
