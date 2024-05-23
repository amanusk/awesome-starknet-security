<div align="center">
<img alt="starknet logo" src="./assets/starknet.svg" width="200" >

  <h1 align="center">Awesome Starknet Security</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/amanusk/awsome-starknet-security/workflows/Build/badge.svg">
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
* [CTFs and Wargames](#ctfs-and-wargames)
  * [CTFs](#ctfs)
  * [CTF writeups](#ctf-writeups)
  * [Wargames](#wargames)
* [Audit reports](#audit-reports)
  * [Cairo](#cairo)
  * [Cairo 0](#cairo-0)
* [Blogposts and Tutorials](#blogposts-and-tutorials)
    * [Writeups](#writeups)
  * [Video tutorials](#video-tutorials)
  * [Twitter threads](#twitter-threads)
* [General](#general)
  * [Repositories and Examples](#repositories-and-examples)
* [License](#license)

<!-- vim-markdown-toc -->

## Tools

<!-- please order alphabetically -->

- [Aegis](https://lindylabs.net/articles/introducing-aegis) - Cairo Formal verification tool.
- [amarna](https://github.com/crytic/amarna) - Static-analyzer and linter for the Cairo programming language.
- [Cairo Fuzzer](https://github.com/FuzzingLabs/cairo-fuzzer) - Cairo Fuzzing tool.
- [cairovm.codes](https://cairovm.codes/) - Compile and debug Sierra code.
- [Caracal](https://github.com/crytic/caracal) - Static analyzer tool over Sierra.
- [Semgrep](https://semgrep.dev/blog/2023/semgrep-now-supports-cairo-1-0/) - Static analyzer for Cairo.
- [sierra-analyzer](https://github.com/FuzzingLabs/sierra-analyzer) - Security toolkit in Rust for analyzing Sierra files.
- [Starknet-Foundry](https://github.com/foundry-rs/starknet-foundry) - Starknet contracts development toolkit.
- [StarkRekt](https://starkrekt.com/) - Check and reset their token spending permissions on Starknet.
- [StarkRevoke](https://www.starkrevoke.com/) - Token revocation tool for Starknet.
- [Thoth](https://github.com/FuzzingLabs/thoth) - Decompiler and security toolkit.

## CTFs and Wargames

### CTFs

<!-- please order alphabetically -->

- [Curta puzzle #13: Ping Pong](https://www.curta.wtf/puzzle/13) - Starknet messaging challenge.
- [Paradigm CTF 2022](https://github.com/paradigmxyz/paradigm-ctf-2022) - Paradigm CTF with Solidity and Cairo challenges.
- [StarknetCC-CTF Lisbon 2022](https://github.com/starknet-edu/starknet-cc-ctf-challenges) - Lisbon 2022 Cairo CTF.

### CTF writeups

- [StarknetCC-CTF](https://github.com/pscott/StarknetCC-CTF) - StarknetCC 2022 CTF writeup by pscott.
- [StarknetCC-CTF](https://blog.ledger.com/starknet-ctf/) - StarknetCC 2022 CTF writeup by Ledger.

### Wargames

- [cairo-damn-vulnerable-defi](https://github.com/credence0x/cairo-damn-vulnerable-defi) - Cairo and Starknet challenges inspired by Capture the Ether.
- [Node Guardians](https://nodeguardians.io/dev-hub?s=devhub-campaigns) - Online wargame and challenge with quests and standalone challenges.
- [Starknet-Security-Challenges](https://starknet-challenges.vercel.app/) - Cairo and Starknet challenges inspired by Capture the Ether.
- [Underhanded Cairo](https://cairopractice.com/tags/security/) - Cairo challenges in cairopractice.com.

## Audit reports

### Cairo

- [Argent Account and Multisig](https://github.com/argentlabs/argent-contracts-starknet/blob/main/audit/Consensys-Diligence-argent-audit-2023-05.pdf) - Argent account and Argent Multisig for Starknet audit by Consensys Diligence.

- [AVNU](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0141-FINAL_AVNU.pdf) - AVNU audit by Nethermind.

- [Carmine](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0153-FINAL_CARMINE.pdf) - Carmine audit by Nethermind.

- [Nimbora](https://github.com/Cairo-Security-Clan/Audit-Portfolio/blob/main/Nimbora%20Audit%20Report.pdf) - Nimbora V2 report by Cairo- Security-Clan.

- [Opus](https://code4rena.com/audits/2024-01-opus#top) - Opus Code4rena contest report.

- [Pragma](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0147-FINAL_PRAGMA.pdf) - Pragma oracle audit by Nethermind.

- [Unruggable.meme](https://github.com/keep-starknet-strange/unruggable.meme/tree/main/packages/contracts/audits) - Unruggable meme protocol community audits by Antoine M., Credennce0x, 0xerim.

- [ZKX](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0120-FINAL_ZKX.pdf) - ZKX audit by Nethermind.

### Cairo 0

- [Briq](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0053-FINAL_BRIQ_PROTOCOL.pdf) - Briq protocol audit by Nethermind.

- [ChainSecurity DAI Bridge Audit](https://chainsecurity.com/wp-content/uploads/2021/12/ChainSecurity_MakerDAO_StarkNet-DAI-Bridge_audit.pdf) - MakerDAO's DAI bridge audit by ChainSecurity.

- [Empiric Netowrk](https://github.com/Zellic/publications/blob/master/Empiric%20Oracle%20-%20Zellic%20Audit%20Report.pdf) - Empiric network audit by Zellic.

- [SithSwap](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0057%20-%20FINAL_SITHSWAP.pdf) - SithSwap AMM by Nethermind.

- [SHA256 from Cartridge](https://github.com/NethermindEth/PublicAuditReports/blob/main/NM0061-DRAFT_CARTDRIGE.pdf) - audit of SHA-256 implementation from Cartridge by Nethermind.

## Blogposts and Tutorials

#### Writeups

- [Adventures with Account Abstraction – Risks and Mitigations in `__validate__`](https://braavos.app/adventures-with-account-abstraction-failed-transactions/) - Considerations for `__validate__` function of Starknet smart accounts.
- [Auditing Cairo 1.0 Contracts](https://extropy-io.medium.com/auditing-cairo-1-0-contracts-9cfdf479924a) - Cairo auditing tips and pitfalls.
- [Cairo 0.x Security](https://ctrlc03.github.io/post/cairo-security/) - Cairo 0.x pitfalls and considerations.
- [Cairo Contracts and pitfalls overview](https://mixbytes.io/blog/cairo-contracts-overview) - Cairo traps and vulnerabilities.
- [Cairo: the Starknet way to writing safe code](https://medium.com/nethermind-eth/cairo-the-starknet-way-to-writing-safe-code-8169486c7132) - Comparing Cairo and Solidity for smart contracts.
- [Introduction to Cairo 1 smart-contracts security](https://antoinemecker.medium.com/an-introduction-to-cairo-1-smart-contracts-security-1f96792b998a) - Introduction to Cairo 1 security, tips and considerations.
- [Under the hood of Cairo 1](https://medium.com/nethermind-eth/under-the-hood-of-cairo-1-0-exploring-sierra-7f32808421f5) - Understanding Sierra code.
- [Zero-Click Argent-X Wallet Contract Vulnerability, Explained](https://braavos.app/zero-click-argent-x-wallet-contract-vulnerability-explained/) - Vulnerability in implementing Starknet smart account.

### Video tutorials

- [Cairo Security (Peteris Erins)](https://www.youtube.com/watch?v=9CIhHNrliW4) - Spearbit seminar on Cairo security.
- [Code4rena x Starknet Basecamp](https://www.youtube.com/playlist?list=PLRbIHW0ATr84DxXQhnH9qf90vQ1l1h90U) - Starknet basecamp for first Cairo contest.

### Twitter threads

## General

### Repositories and Examples

- [not-so-smart-cairo](https://github.com/crytic/building-secure-contracts/tree/master/not-so-smart-contracts/cairo) - Examples of common Cairo smart contract vulnerabilities by Trail of Bits.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law,
[amanusk](https://github.com/amanusk) has waived all copyright
and related or neighboring rights to this work.
