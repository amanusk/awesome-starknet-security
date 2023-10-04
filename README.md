kdiv align="center">
<img alt="starknet logo" src="./assets/starknet.svg" width="200" >

  <h1 align="center">Awesome Starknet Security</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/amanusk/awesome-starknet-security/workflows/Build/badge.svg">
    </a>
    <a href="https://github.com/amanusk/awesome-starknet-security/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/amanusk/awesome-starknet-security">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">A curated list of awesome Starknet security resources, tools, CTFs and more.</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

</div>

### Contents

<!-- vim-markdown-toc GFM -->

* [Tools](#tools)
* [Tutorials and CTFs](#tutorials-and-ctfs)
  * [CTFs](#ctfs)
    * [Cairo](#cairo)
    * [Cairo 0](#cairo-0)
    * [CTF writeups](#ctf-writeups)
* [Audit reports](#audit-reports)
  * [Cairo](#cairo-1)
  * [Cairo 0](#cairo-0-1)
* [General](#general)
  * [Repositories and Examples](#repositories-and-examples)
  * [Blogposts and Tutorials](#blogposts-and-tutorials)
  * [Twitter threads](#twitter-threads)
* [License](#license)

<!-- vim-markdown-toc -->

## Tools

<!-- please order alphabetically -->

- [Aegis](https://lindylabs.net/articles/introducing-aegis) - Cairo Formal verification tool.
- [amarna](https://github.com/crytic/amarna) - Static-analyzer and linter for the Cairo programming language.
- [Cairo Fuzzer](https://github.com/FuzzingLabs/cairo-fuzzer) - Cairo Fuzzing tool.
- [Caracal](https://github.com/crytic/caracal) - Static analyzer tool over Sierra.
- [Semgrep](https://semgrep.dev/blog/2023/semgrep-now-supports-cairo-1-0/) - Static analyzer for Cairo.
- [Starknet-Foundry](https://github.com/foundry-rs/starknet-foundry) - Starknet contracts development toolkit.
- [Thoth](https://github.com/FuzzingLabs/thoth) - Decompiler and security toolkit.

## Tutorials and CTFs

### CTFs

#### Cairo

<!-- please order alphabetically -->

- [cairo-damn-vulnerable-defi](https://github.com/credence0x/cairo-damn-vulnerable-defi)
- [Curta puzzle #13: Ping Pong](https://www.curta.wtf/puzzle/13)
- [Node Guardians](https://nodeguardians.io/dev-hub?s=devhub-campaigns)
- [Starknet-Security-Challenges](https://starknet-challenges.vercel.app/)

#### Cairo 0

- [Paradigm CTF 2022](https://github.com/paradigmxyz/paradigm-ctf-2022)
- [StarknetCC-CTF Lisbon 2022](https://github.com/starknet-edu/starknet-cc-ctf-challenges)

#### CTF writeups

- [StarknetCC-CTF](https://github.com/pscott/StarknetCC-CTF) - StarknetCC 2022 CTF writeup by pscott.
- [StarknetCC-CTF](https://blog.ledger.com/starknet-ctf/) - StarknetCC 2022 CTF writeup by Ledger.

## Audit reports

### Cairo

### Cairo 0

<!-- please order by most recent first -->

- [Empiric Netowrk](https://github.com/Zellic/publications/blob/master/Empiric%20Oracle%20-%20Zellic%20Audit%20Report.pdf) - Empiric network audit by Zellic.
- [ChainSecurity DAI Bridge Audit](https://chainsecurity.com/wp-content/uploads/2021/12/ChainSecurity_MakerDAO_StarkNet-DAI-Bridge_audit.pdf) - MakerDAO's DAI bridge audit by ChainSecurity.

## General

### Repositories and Examples

- [not-so-smart-cairo](https://github.com/crytic/building-secure-contracts/tree/master/not-so-smart-contracts/cairo) - Examples of common Cairo smart contract vulnerabilities by Trail of Bits.

### Blogposts and Tutorials

- [Cairo Contracts and pitfalls overview](https://mixbytes.io/blog/cairo-contracts-overview)
- [Cairo 0.x Security](https://ctrlc03.github.io/post/cairo-security/)
- [Under the hood of Cairo 1](https://medium.com/nethermind-eth/under-the-hood-of-cairo-1-0-exploring-sierra-7f32808421f5)
- [Auditing Cairo 1.0 Contracts](https://extropy-io.medium.com/auditing-cairo-1-0-contracts-9cfdf479924a)
- [Risks and mitigations in `__validate__`](https://braavos.app/adventures-with-account-abstraction-failed-transactions/)
- [ArgentX `__validate__` vulnerability](https://braavos.app/zero-click-argent-x-wallet-contract-vulnerability-explained/)

### Twitter threads

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law,
[amanusk](https://github.com/amanusk) has waived all copyright
and related or neighboring rights to this work.
