Awesome Lisk
===============
A curated list of Lisk resources, services and tools for software developers

![Lisk Logo](https://lisk.io/sites/default/files/pictures/2019-10/Styleguide-LiskLogo_1_0.svg)

List of content

- [Useful Links](#Useful-Links)
- [Framework: lisk-sdk](#Framework:-lisk-sdk)
- [Interoperability and Lisk DEX](#Interoperability-and-Lisk-DEX)
- [lisk-sdk dapps](#lisk-sdk-dapps)
- [lisk-sdk development tools](#lisk-sdk-development-tools)
- [LSK and Token sharing / pool software](#LSK-and-Token sharing-/-pool-software)
- [Custom libraries](#Custom-libraries)
- [Wallets](#Wallets)
- [Node managment and forging](#Node-managment-and-forging)
- [Network monitors](#Network-monitors)
- [Transaction-asset - custom usage](#Transaction.asset---custom-usage)
- [Vanitygens](#Vanitygens)
- [Useful scripts](#Useful-scripts)
- [Blockchain analysis](#Blockchain-analysis)
- [Misc](#Misc)
- [Legacy repositories](#Legacy-repositories)
- [Contributing](#Contributing)

# Useful Links

### Official

* [Lisk.io](https://lisk.io) Official Lisk website.
* [Blog.lisk.io](https://blog.lisk.io) Official Lisk blog.
* [Lisk Discord server](https://discordapp.com/invite/7EKWJ7b) Official Lisk Discord server, operated by LiskHQ.
* [Lisk Documentation](https://lisk.io/documentation/) Official Lisk documentation.
* [Lisk Github](https://github.com/LiskHQ) Official Lisk Github.

### Ecosystem

* [ThePool Discord server](https://discord.gg/XWMmS8X) Official ThePool delegate team chat server on Discord, related mostly to dapp development.
* [Lisk Center Utrecht](https://www.liskcenter.io) LCU the blockchain hub of the Netherlands.

# Framework: lisk-sdk
* [lisk-sdk](https://github.com/LiskHQ/lisk-sdk) Github repository with lisk-sdk framework to develop dapps.
* [lisk-explorer](https://github.com/LiskHQ/lisk-explorer) Github repository with lisk-explorer, compatible with lisk-sdk to browse blockchain data.
* [lisk-docs](https://github.com/LiskHQ/lisk-docs) Official docs repository.
* [lisk-core](https://github.com/LiskHQ/lisk-core) Main network application built with lisk-sdk.
* [lisk-scripts](https://github.com/LiskHQ/lisk-scripts) Useful lisk related bash scripts.
* [lips](https://github.com/LiskHQ/lips) Lisk improvement proposal repository.
* [lisk-template](https://github.com/LiskHQ/lisk-template) Lisk repository template.

# Interoperability and Lisk DEX
* [lisk-dex](https://github.com/jondubois/lisk-dex) Community driven, module compatible with lisk-sdk to enable DEX functionality between main and side chains. Utilising 2-way federated peg.
* [lisk-dex-http-api](https://github.com/jondubois/lisk-dex-http-api) Http api module for [lisk-dex](https://github.com/jondubois/lisk-dex).
* [lisk-interchain](https://github.com/jondubois/lisk-interchain) Community driven, custom peer selector plugin for Lisk. Used by [lisk-dex](https://github.com/jondubois/lisk-dex).
* [capitalisk](https://github.com/jondubois/capitalisk) Capitalisk sidechain as a Lisk interchain module, developed with [lisk-sdk](https://github.com/LiskHQ/lisk-sdk) with [lisk-interchain](https://github.com/jondubois/lisk-interchain) and [lisk-dex](https://github.com/jondubois/lisk-dex).

# lisk-sdk dapps
* [ldice](https://github.com/thepool-io/ldice) Proof of concept of provably fair dice game, developed by [ThePool](https://thepool.io) delegate.
* [lisk-sdk-examples](https://github.com/LiskHQ/lisk-sdk-examples) Example applications built using the Lisk software development kit, developed by LiskHQ.
* [lisk-bike](https://github.com/JesusTheHun/lisk-bike) Decentralised bike sharing.
* [LQuiz](https://github.com/lisknonanika/LQuiz) Quiz proof of concept.
* [lisk-bike-blockchain-app](https://github.com/bartwr/lisk-bike-blockchain-app) Decentralised bike sharing.
* [lisk-roulette](https://github.com/corbifex/lisk-roulette) Proof of Concept roulette made with the Lisk SDK, developed by Moosty delegate team.

# lisk-sdk development tools
* [lisk-transaction-faucet](https://github.com/JesusTheHun/lisk-transaction-faucet) Custom transaction faucet
* [lisk-genesis](https://github.com/corbifex/lisk-genesis) Useful library to generate genesis block to start new network. Developed by Corbifex from Moosty delegate team.
* [lisk-boilerplate](https://github.com/corbifex/lisk-boilerplate) Lisk node boilerplate to start development. Developed by Corbifex from Moosty delegate team.
* [lisk-bootstrap](https://github.com/JesusTheHun/lisk-bootstrap) A simple straight forward setup for developing a Lisk Blockchain.
* [randolisk](https://github.com/jondubois/randolisk) Decentralized random number generator for Lisk interchain.
* [prando](https://github.com/zeh/prando) Deterministic pseudo-random number generator for JavaScript and TypeScript. Useful with lisk-sdk.

# LSK and Token sharing / pool software
* [liskpool](https://github.com/thepool-io/liskpool) Advanced pool sharing software, written in php. Using [lisk-php](https://github.com/thepool-io/lisk-php) and [liskpool-html](https://github.com/thepool-io/liskpool-html), developed by [ThePool](https://thepool.io) delegate.
* [liskpool-html](https://github.com/thepool-io/liskpool-html) HTML interface for [liskpool](https://github.com/thepool-io/liskpool).
* [lisk-pool](https://github.com/dakk/lisk-pool) Pool / sharing software written in JavaScript.
* [yet-another-lisk-pool](https://github.com/alepop/yet-another-lisk-pool) Pool / sharing software written in JavaScript.
* [pyliskpool](https://github.com/slasheks/pyliskpool) Pool / sharing software written in Python.
* [liskpool-goforlisk](https://github.com/goforlisk/liskpool) Pool / sharing software developed by goforlisk.
* [lisk-reward-distributor](https://github.com/Lemii/lisk-reward-distributor) Automatically calculate and distribute forging rewards among voters.
* [lisk-delegate-payouts](https://github.com/Lemii/lisk-delegate-payouts) Calculate voting rewards for individual delegates and pools
* [liskit-pool](https://github.com/andreafspeziale/liskit-pool) Python script collection of the Lisk Liskit pool with [lisk-dashboard](https://github.com/andreafspeziale/liskit-dashboard).
* [Lisk-fundsDistributor](https://github.com/simonmorgenthaler/Lisk-fundsDistributor) Python script to automatically distribute funds to different accounts.

# Custom libraries
* [lisk-php](https://github.com/thepool-io/lisk-php) PHP library and cli interface to interact with Lisk network, developed by [ThePool](https://thepool.io) delegate.
* [lisk-swift](https://github.com/AndrewBarba/lisk-swift) Swift library to interact with Lisk network.
* [LiskPHP](https://github.com/cb0/LiskPHP) PHP library, developed by cb0.
* [lisk-go](https://github.com/liskascend/lisk-go) GO library to interact with Lisk network.
* [pylisk](https://github.com/slasheks/pylisk) Python library to interact with Lisk network.
* [SwiftyLisk](https://github.com/LiskUser1234/SwiftyLisk) Swift library to interact with Lisk network.
* [lisk-php-goforlisk](https://github.com/goforlisk/lisk-php) PHP library, developed by goforlisk.
* [lisk-api-rust-client](https://github.com/ManuGowda/lisk-api-rust-client) Rust API Client for accessing Lisk Blockchain.
* [RxLisk-iOS](https://github.com/sayler8182/RxLisk-iOS) Swift 5 library for Lisk Blockchain
* [lisk-hd-key](https://github.com/lisk-builders/lisk-hd-key) Key Derivation for Lisk coin.
* [liskapi](https://github.com/dakk/liskapi) A smart wrapper for Lisk node APIs.
* [dpos-api-wrapper](https://github.com/vekexasia/dpos-api-wrapper) An API Wrapper library for Lisk derived blockchains.
* [cryptobaguette/lisk-graphql](https://github.com/cryptobaguette/lisk-graphql) A realtime GraphQL api on top of the Lisk blockchain.
* [ciocan/lisk-graphql](https://github.com/ciocan/lisk-graphql) Lisk GraphQL Server.
* [lisk-api-elixir-client](https://github.com/ManuGowda/lisk-api-elixir-client) Elixir API Client for accessing Lisk Blockchain.
* [wamp-socket-cluster](https://github.com/LiskHQ/wamp-socket-cluster) Wrapper for both WAMPClient and WAMPServer.
* [lisk-avatar](https://github.com/tobiaslins/lisk-avatar) Generate Lisk Avatars from your Lisk ID.

# Wallets
* [Lisk for desktop](https://github.com/LiskHQ/lisk-desktop) Lisk wallet for desktop, developed by LiskHQ.
* [Lisk mobile wallet](https://github.com/LiskHQ/lisk-mobile) Mobile wallet, developed by LiskHQ.
* [liskish-wallet](https://github.com/hirishh/liskish-wallet) Desktop wallet developed by delegate Hirishh. Based on old Lisk Nano.
* [lisk-mobile](https://github.com/liskarchitect/lisk-mobile) Mobile wallet developed by liskarichtect.
* [liskpaperwallet](https://github.com/rferro/liskpaperwallet) Lisk offline paper wallet generator.
* [LiskPaper](https://github.com/nerdvibe/LiskPaper) Lisk offline paper wallet generator.
* [Lisk-GDT-Wallet](https://github.com/mrv777/Lisk-GDT-Wallet) Wallet developed by GDT.
* [lisk-offline](https://github.com/nerdvibe/lisk-offline) Offline wallet for Lisk.
* [ledger-wallet-lisk](https://github.com/bradleat/ledger-wallet-lisk) Wallet for Ledger hardware device.
* [LiskTrezor-CLI-wallet-manager](https://github.com/thepool-io/LiskTrezor-CLI-wallet-manager) CLI to manage wallets on Trezor T. It allows many custom functions.
* [Lisk-offline-transaction-signing-tool](https://github.com/mrgrshift/Lisk-offline-transaction-signing-tool) Tool to sign offline the Lisk cryptocurrency transactions and optionally tool to broadcast online.
* [lisk-multisig](https://github.com/andreafspeziale/lisk-multisig) Local web app for Lisk multi-signature accounts.
* [lisk-buttons](https://github.com/lisk-builders/lisk-buttons) Lisk Buttons allow you to open Lisk Nano wallet with pre-filled forms.

# Node managment and forging

### Managment

* [lisk-cute-assistant](https://github.com/nerdvibe/lisk-cute-assistant) A cute Lisk Core Assistant for remote Node Management via Telegram
* [liskit-bot](https://github.com/andreafspeziale/liskit-bot) Simple telegram bot of the Lisk Liskit environment to retrieve info about your delegate.
* [lisk-rebuilder](https://github.com/sidechain-solutions/lisk-rebuilder) Ensures your node is in sync and up-to-date with the network.
* [lisk-redphone](https://github.com/hirishh/lisk-redphone) Lisk - RedPhone is a delegate utility that make calls if node is not forging
* [Lisk-Observer](https://github.com/Liskers/Lisk-Observer) Node monitor.
* [Lisk-heightChecker](https://github.com/simonmorgenthaler/Lisk-heightChecker) Bash script to check the blockheight and Lisk version on configured nodes.
* [snapshot-validator](https://github.com/webmaster128/snapshot-validator) Very efficient blockchain snapshot validator written in C.
* [lisk-nomo](https://github.com/lisk-builders/lisk-nomo) Node monitor for nomo downtime. Lisk Nomo is tailored for the new Lisk Core 1.x release.
* [Missed-Block-Alarm-Lite](https://github.com/MorinelloA/Missed-Block-Alarm-Lite) Lightweight Missed Block Checker for Lisk.
* [lite-lisk-checker](https://github.com/biolypl/lite-lisk-checker) Lite Lisk checker is small bot utilizing [lisk-elements](https://github.com/LiskHQ/lisk-elements) and [Telegram bot - telebot](https://github.com/mullwar/telebot) to check syncing and optionally forging status of your Lisk nodes.

### Forging

* [Lisk-forging-failover](https://github.com/thepool-io/Lisk-forging-failover) Forging managing software, written in PHP with good practices. It allows to set up array of forging nodes and efficiently switch forging node in case of any problems on main server. 
* [always-forge](https://github.com/4miners/always-forge) One of the very first forging managers, developed by 4miners delegate.
* [liskak](https://github.com/filipealmeida/liskak) Lisk Army Knife - Forging failover and command line lisk
* [lisk-dfc](https://github.com/sidechain-solutions/lisk-dfc) Control and monitor an array of forgers, developed by Sidechain Solutions.
* [lisk-autotoggler](https://github.com/Lemii/lisk-autotoggler) A script that ensures that forging on your Lisk node stays enabled.
* [Lisk-Enable-Forging](https://github.com/S3x0r/Lisk-Enable-Forging) Tool to Enable Forging on Lisk Node.
* [lisk-passphrase-encrypt](https://github.com/prolina-foundation/lisk-passphrase-encrypt) Custom software to encrypt passphrase for forging.
* [forger_lisk](https://github.com/davilinfo/forger_lisk) Set lisk forging status.
* [salty-dpos](https://github.com/slasheks/salty-dpos) SaltyDPOS - DPOS node management with Saltstack.

# Network monitors
* [lisk-network-stats](https://github.com/thepool-io/lisk-network-stats) Javascript based, network monitor. [Liskstats.net](https://liskstats.net)
* [lisk-network-reporter](https://github.com/thepool-io/lisk-network-reporter) Javascript based, reporting software for [lisk-network-stats](https://github.com/thepool-io/lisk-network-stats)
* [lisk-unconfirmed](https://github.com/thepool-io/lisk-unconfirmed) Very basic html app to see current unconfirmed transactions on Lisk network.
* [lisk-stat-frontend](https://github.com/sdrpa/lisk-stat-frontend) React front-end for http://oatc.io/lisk-stat/, developed by sdrpa.
* [lisk-stat-backend](https://github.com/sdrpa/lisk-stat-backend) Swift (Kitura) back-end service for [lisk-stat-frontend](https://github.com/sdrpa/lisk-stat-frontend).
* [lisk-node-monitor](https://github.com/sdrpa/lisk-node-monitor) iOS Lisk node monitor.
* [LiskMonitor](https://github.com/Gr33nDrag0n69/LiskMonitor) PowerShell Stand-Alone Lisk Nodes & Delegates Monitoring, developed by Gr33nDrag0n69.
* [lisk-delegate-monitor](https://github.com/dakk/lisk-delegate-monitor) Web platform for lisk delegates.
* [Lisk-Delegate-Visualization](https://github.com/Korben3/Lisk-Delegate-Visualization) A visualization of the top 202 forging and standby delegates.
* [lisk-argus](https://github.com/lisk-builders/lisk-argus) Lisk Argus is a monitoring software that keeps track of the Lisk network.

# Transaction-asset - custom usage
* [lisk-file-manager](https://github.com/Lemii/lisk-file-manager) Software to manage files in Lisk blockchain.
* [lisk-tic-tac-toe](https://github.com/sidechain-solutions/lisk-tic-tac-toe) tic tac toe game built only using transaction data field.
* [PayWithLisk-Server](https://github.com/sdrpa/PayWithLisk-Server) Server to process payments with Lisk blockchain.
* [Lisk-Download-File](https://github.com/S3x0r/Lisk-Download-File) Software to download files from Lisk blockchain, uploaded in transactions data field.
* [Lisk-Send-File](https://github.com/S3x0r/Lisk-Send-File) Software to upload files to Lisk blockchain, uploaded to transactions data field.
* [liskPay2Enter](https://github.com/Korben3/liskPay2Enter) Utilisation of transaction asset to unlock digital content.
* [LiskPay2Download](https://github.com/Korben3/LiskPay2Download) Utilisation of transaction asset to unlock download of digital content.
* [lisk-eternity](https://github.com/vekexasia/lisk-eternity) Guestbook like software to store entries and present on website.
* [liskwall](https://github.com/Korben3/liskwall) Send short messages to the liskwall using the data field.
* [liskland](https://github.com/Korben3/liskland) Liskland allows users to add objects to a website using the reference code in a lisk transaction.

# Vanitygens
* [lisk-vanity](https://github.com/webmaster128/lisk-vanity) A tool to generate short Lisk addresses with GPU support.
* [node-lisk-vanitygen](https://github.com/rwilinski/node-lisk-vanitygen) Simple JS vanitygen.
* [PyLiskShortAddressGen](https://github.com/Nimbus76/PyLiskShortAddressGen) Short address generator, written in Python.
* [lisk-shorty](https://github.com/4fryn/lsk-shorty) Pure rust-tool to brute-force short Lisk addresses.
* [lisk-php-cli](https://github.com/thepool-io/lisk-php) Interface to interact with Lisk network via command line. Complex but slow vanitygen function.

# Useful scripts
* [LiskScripts](https://github.com/mrv777/LiskScripts) Scripts for Lisk Delegate Servers, developed by mrv777.
* [Lisk-autoVote](https://github.com/simonmorgenthaler/Lisk-autoVote) Script to vote automatically positive and negative from text files with delegate names, addresses and/or public keys.
* [lisk-recovery](https://github.com/lukeliasi/lisk-recovery) Tool to recover a Lisk passphrase with a missing word.
* [lisk-rescue](https://github.com/nerdvibe/lisk-rescue) Recover Lisk funds from non conventional passphrases
* [lisk-passphrase-recovery](https://github.com/slaweet/lisk-passphrase-recovery) Recover a 12-word Lisk passphrase with exactly one incorrect word.
* [lisk-tools](https://github.com/corsaro1/lisk-tools) Various scripts from corsaro delegate.
* [lisk_broadcast](https://github.com/corsaro1/lisk_broadcast) Broadcast a tx on lisk network.
* [liskitbash](https://github.com/liskitaliangroup/liskitbash) Very simple bash script wrapper for Lisk client auto update or install.
* [Lisk-multiSigner](https://github.com/simonmorgenthaler/Lisk-multiSigner) Sign multiple pending multisig transactions automatically in one batch.
* [lisk-php-cli](https://github.com/thepool-io/lisk-php) Interface to interact with Lisk network via command line.

# Blockchain analysis
* [MorinelloA/lisk-voter-weight-distribution](https://github.com/MorinelloA/lisk-voter-weight-distribution) Simple UI to view voters of a Lisk delegate by their vote weight.
* [Balance-History](https://github.com/MorinelloA/Balance-History) Tool to check the balance of any Lisk address from any moment in time.
* [LiskRichList](https://github.com/MorinelloA/LiskRichList) Top rich wallets.
* [LiskPending-NewUI](https://github.com/MorinelloA/LiskPending-NewUI) Pending rewards.
* [lisk-accounting](https://github.com/slasheks/lisk-accounting) Lisk delegate accounting helpers.
* [lisk-export](https://github.com/tobiaslins/lisk-export) Export your Lisk transactions as CSV.
* [lisk-voters](https://github.com/andreafspeziale/lisk-voters) Voters difference between two addresses.

# Misc

* [lisk-ticker](https://github.com/lisk-builders/lisk-ticker) A simple Chrome Extension showing current Lisk price ticker.
* [lisk-countdown](https://github.com/nerdvibe/lisk-countdown) Simple block-height countdown for Lisk blockchain.
* [lisk-c64](https://github.com/hirishh/lisk-c64) Little tool for Lisk with a C64 like interface.
* [lisk-builders](https://github.com/lisk-builders/lisk-builders) A complete directory of Lisk delegates that also actively contribute [https://lisk.builders](https://lisk.builders/)
* [Lisk-Core-OpenBSD](https://github.com/S3x0r/Lisk-Core-OpenBSD) Tutorial how to install Lisk Core node on OpenBSD 6.4 amd64.
* [lisk-faucet](https://github.com/LiskHQ/lisk-faucet) Lisk faucet with captcha.
* [docker-lisk-php](https://github.com/karek314/docker-lisk-php) Docker for Lisk-PHP CLI.

# Legacy repositories

* [LiskArchive](https://github.com/LiskArchive) Official LiskHQ repository for deprecated projects and libraries.

# Contributing

If you would like to modify description or classification, please provide pull request. If you would like to add project, please submit issue or pull request.

Awesome-Lisk is prepared and maintained by [ThePool](https://thepool.io) Lisk delegate team.

### License: MIT
