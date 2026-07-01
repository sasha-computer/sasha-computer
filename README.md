<img src="./personal-software.png" width="300" />

# Hi, I'm Sasha

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

~5 years as a technical generalist in cryptography and developer infrastructure, communicating and organising across teams and communities.

## Featured Projects

### Web

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2025/tree/main/hypergrid">Hypergrid</a></h3>
      <p>Interactive personal site concept. Roll a 3D cube across an 8x8 grid with arrow keys. Landing on highlighted tiles reveals content panels. Pivot-point roll animations with eased quaternion interpolation and per-face materials.</p>
      <p><sub>SvelteKit · Three.js · TypeScript</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2025/tree/main/nn">Neural Nets from Scratch</a></h3>
      <p>Working through Karpathy's Zero to Hero series. Built a custom autograd engine with backpropagation (addition, multiplication, power, tanh), then a multi-layer perceptron. Also tried tinygrad for GPU tensor ops on Apple Metal.</p>
      <p><sub>Python · NumPy · tinygrad</sub></p>
    </td>
  </tr>
</table>

### Tooling

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2026/tree/main/gandalf">Gandalf</a></h3>
      <p>Personal AI assistant on Discord and WhatsApp. Reworked from NanoClaw with durable memory (QMD search), per-group message queues with SQLite state, native subprocess execution, and graceful shutdown.</p>
      <p><sub>TypeScript · Bun · SQLite · Claude API</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2026/tree/main/pdfcards">PDFCards</a></h3>
      <p>Local PDF reader with highlighting and spaced repetition flashcards. Highlight text, turn highlights into flashcards, review them with SRS. Built after watching Dwarkesh Patel and Andy Matuschak talk about studying.</p>
      <p><sub>Bun · TypeScript · pdf.js</sub></p>
    </td>
  </tr>
</table>

### ZK & Cryptography

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2025/tree/main/browser-verifier">In-Browser ZK Verifier</a></h3>
      <p>Compiles a RISC Zero verifier to WebAssembly and runs it in a Next.js app. Proves the 1,000,000th Fibonacci number, then verifies the proof in the browser faster than recomputing it. <a href="https://www.youtube.com/watch?v=aTCPCf8ff-c">Video walkthrough</a>.</p>
      <p><sub>Rust · R0VM · wasm-pack · WebAssembly · Next.js</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/hurricane-money">Hurricane Money</a></h3>
      <p>Tornado Cash-style mixer built on OpenVM. A learning exercise to understand how mixing protocols work on a custom VM.</p>
      <p><sub>Solidity · OpenVM</sub></p>
    </td>
  </tr>
</table>

### Blockchain & DeFi

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2022/tree/main/robotrust">BAM! Trust</a></h3>
      <p>Grantor Retained Annuity Trusts (GRATs) as smart contracts on Arbitrum. Deployer contract, financial math helpers, and Chainlink oracle integration for real-world asset pricing. React frontend for deploying and managing trust instances on-chain.</p>
      <p><sub>Solidity · Hardhat · Chainlink · Arbitrum · React</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sasha-computer/2022/tree/main/erc4337">ERC-4337 Account Abstraction</a></h3>
      <p>Barebones ERC-4337 implementation. Custom <code>SimpleWallet.sol</code> with <code>validateUserOp</code> logic, an <code>EntryPoint</code> contract, and a bundler script targeting Goerli. Built to learn the core mechanics.</p>
      <p><sub>Solidity · Hardhat · Ethers.js</sub></p>
    </td>
  </tr>
</table>

## More Projects

- [readwise-triage](https://github.com/sasha-computer/readwise-triage) - Swipe through your Readwise Reader inbox like Tinder. SQLite + AI summaries.
- [sidebar](https://github.com/sasha-computer/sidebar) - Permanent macOS desktop sidebar in a Hammerspoon webview. Svelte 5 + Tailwind.
- [domain-search](https://github.com/sasha-computer/domain-search) - Search every TLD for available domains in the terminal. Async DNS + RDAP.
- [plain-text-running-tracker](https://github.com/sasha-computer/plain-text-running-tracker) - Parse Apple Health + Garmin FIT exports into a markdown running log.
- [x-likes](https://github.com/sasha-computer/x-likes) - Full-text search 13K+ X/Twitter likes from the terminal. SQLite FTS5 + fzf.
- [runelite-firemaking](https://github.com/sasha-computer/runelite-firemaking) - RuneLite plugin tracking firemaking session stats. Java.
- [vocs search fix](https://github.com/sasha-computer/vocs) - Fixed broken search indexing in Vocs docs framework. 270+ downloads.
- [create-steel-app](https://github.com/sasha-computer/2024/tree/main/create-steel-app) - One-command setup for ZK execution proof apps on Ethereum. RISC Zero + Foundry.
- [teztap](https://github.com/sasha-computer/2024/tree/main/teztap) - Rust rewrite of the Tezos testnet faucet tool. Fast.
- [ecdsa-exchange](https://github.com/sasha-computer/2021/tree/main/ecdsa-exchange) - Client-server exchange using real ECDSA cryptography for auth. Where it started.
- [arbitrum-nft-warranties](https://github.com/sasha-computer/2022/tree/main/arbitrum-nft-warranties) - NFT-based product warranties on Arbitrum. Immutable and transferable.
- [escrow](https://github.com/sasha-computer/2022/tree/main/escrow) - Carbon credit escrow on Algorand. Atomic swap between tokens and payment.

## Year Archives

Everything that isn't its own repo lives in a year monorepo.

**[2021](https://github.com/sasha-computer/2021)** · **[2022](https://github.com/sasha-computer/2022)** · **[2023](https://github.com/sasha-computer/2023)** · **[2024](https://github.com/sasha-computer/2024)** · **[2025](https://github.com/sasha-computer/2025)** · **[2026](https://github.com/sasha-computer/2026)**

## Connect

[![X](https://img.shields.io/badge/-@sasha--computer-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/sasha-computer)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sasha-computer)
