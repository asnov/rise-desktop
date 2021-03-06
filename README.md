# Multi Platform Rise Lite Client

## Download
[Latest Release](https://github.com/RiseVision/rise-desktop/releases)

## Important
If you are testing or you just want to start fresh (you'll loose your addresses so backup your secrets!):
* Start Rise Desktop Client
* Press CONTROL+D to open up the Debug Screen
* Copy and Paste this line to the console box `localStorage.clear();window.location.reload();`

## Features
* Available on ***Windows***, ***Linux*** (ubuntu/debian) and ***Macosx*** (almost done)
* No wait to sync to the network: launch and use.
* view any account from its address (transactions, delegate status and votes)
* (soon) deposit RISE using altcoins or USD (via changer.com) - no registration needed
* label any account
* realtime currency value (updated every 5 min) in UsD, Euro, BTC, HKD, JPY, CNY, AuD, CanD, Pound and Rubble
* autoconnecting to a healthy Rise network peer. If the peer is not good any more, automatically find a new one.
* send RISE from/to any account.
* easily switch to different network, or private chains
* customize background
* isolated processes on Windows and Macosx to prevent from data sniffing or injection.
* Translations (thanks to the Ark community). Please help contributing

If you login to your account (with your passphrase)
* (soon) Withdraw to altcoins or USD (via changer.com) - no registration needed
* Organise your accounts with virtual folders (for instance savings, personnal etc...) so you don't pay any transfer fee
* Update your votes.
* Save your passphrases (unsecured so far, secured vault in the near future)

Second signature supported. Multisignature accounts not yet supported.

## From code

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. Optionally switch to node 6.9.2, because this is currently developped with this version:
```
sudo npm install -g n
sudo n 6.9.2
```

Install from source:
```bash
# Clone this repository
git clone https://github.com/RiseVision/rise-desktop
# Go into the repository
cd rise-desktop
# Install dependencies 
npm install
```

Then start:
```bash
npm start
```

## Necessary to package from Mac OS X

```
brew tap Homebrew/bundle
brew bundle
```

## Authors
- FX Thoorens <fx@ark.io>
- Guillaume Verbal <doweig@ark.io>

## Contributors
- [@lepetitjan](https://twitter.com/lepetitjan)

### License [MIT](LICENSE.md) copyright (c) 2017 RISE, copyright (c) 2016 fx thoorens
