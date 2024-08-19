<p align="center">

<h1 align="center">LMAP</h1>

<p align="center">
    LMAP (large language model mapper) is like NMAP for LLM, is a toolkits for finding LLM 0-Day 10x Faster with adversarial prompt fuzzing.
    <br />
    <br />
We believe that only by continuously adversarial tests and simulated attacks can we expose as many potential risks of LLM as possible and ultimately push LLM Security Alignment towards a safer stage.
<p>
<img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/TrustAI-laboratory/LMAP" />
<img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/TrustAI-laboratory/LMAP" />
<img alt="" src="https://img.shields.io/github/repo-size/TrustAI-laboratory/LMAP" />
<img alt="Downloads" src="https://static.pepy.tech/badge/LMAP" />
<img alt="GitHub Issues" src="https://img.shields.io/github/issues/TrustAI-laboratory/LMAP" />
<img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/TrustAI-laboratory/LMAP" />
<img alt="Github License" src="https://img.shields.io/github/license/TrustAI-laboratory/LMAP" />
</p>


## Core Components
### [1] GUI Tool (Comeing Soon..)
A GUI interface adapted to MacOS, Windows, and Linux platforms.

| Features                                        | Description                                                                                                               | Integrated |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|------------|
| LLM Adapter 🛠️                   |  Configure the target LLM to be tested (such as gpt-4o, Qwen-max, etc), and also include the kwargs (such as Top_k, etc)  | ✅         |
| Manual Testing 🧪                |  Complete manual testing for multiple LLM targets, different prompts and parallel in one interface, eliminating the need to switch between various platforms, web pages, and apps, which improving manual testing efficiency | ✅          |
| Local vulnerability database and replay 🌀  | Supports saving successful jailbreak prompts, forming a local custom vulnerability databases, and supports automatic replay of the local vulnerability databases  | ✅       |

**Note**: Please be aware that Agentic Security is designed as a safety scanner tool and not a foolproof solution. It cannot guarantee complete protection against all possible threats.


### [2] Jailbreak Cloud Service
A Prompt Jailbreak As Service, through SaaS, let every community member and GenAI developer can equally enjoy the most cutting-edge LLM jailbreak technology. 

| Features                                        | Description                                                                                                               | Integrated |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|------------|
| Modules List API                                |  [API](http://lmap.trustai.pro/mutator_list/v1)                                                                           | ✅         |
| Deformer plug-in integration                    |  We refer to the main method of [arXiv:2407.14937](https://arxiv.org/abs/2407.14937), establish a systematic taxonomy of large language model red teaming strategies, and continue to integrate the prompt mutation methods of current academic sota | 🔄           |
| Document  | TBD  | TBD   |

In addition to the GUI tool, you can also integrate the Jailbreak Cloud Service into your own LLM assessment system and dynamically obtain jailbreak words through API interaction.

To make things more interesting, we also developed a playground website: [here](http://lmap.trustai.pro/).

<img width="1272" alt="image" src="https://github.com/user-attachments/assets/085b69e1-6434-4e44-a3a2-1c8c7ecc555f">



## 📦 Installation

TBD

## UI 🧙

TBD

## ⛓️ Quick Start

TBD

## Run as CI check

TBD

## Documentation

For more detailed information on how to use LMAP, including advanced features and customization options, please refer to the official documentation.

## Roadmap and Future Goals

TBD


## Contact us

[Bool a Demo](https://www.trustai.pro/book-a-demo).

Personalized demo slots are limited due to high demand. We'll reach out to you as soon as we can.
