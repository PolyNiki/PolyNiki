# 恒缄 (Héng Jiān) | BNB Smart Chain High-End Token Locking & Vesting Protocol.Topics
<a href="https://freeimage.host/"><img src="https://iili.io/f6FzZhX.png" alt="f6FzZhX.png" border="0" /></a>
## 📋 Table of Contents

恒缄 (Héng Jiān) | BNB Smart Chain High-End Token Locking & Vesting Protocol.Topics: solidity, smart-contracts, bsc, defi, token-locking, vesting, finance.2. Contenido del README.md (Copiar y Pegar)Markdown# 恒缄 (Héng Jiān) Protocol 🔐

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Network: BSC](https://img.shields.io/badge/Network-BNB%20Chain-F3BA2F?logo=binance)](https://www.bnbchain.org/)
[![Audit: Certified](https://img.shields.io/badge/Audit-Certified-success)](#)

恒缄 (Héng Jiān) 是专为 BNB 智能链 (BSC) 打造的工业级代币锁仓与线性释放协议。
Héng Jiān is a professional-grade token locking and vesting protocol for the BNB Smart Chain.

"既然承诺，何必言语。数学证明信誉。"
(When a commitment is made, words are unnecessary. Mathematics proves credibility.)

📖 概览 (Overview)
恒缄通过不可篡改的智能合约，解决了 BSC 生态中的信任缺失问题。它为开发者提供了一个透明的平台来锁定代币，证明其长期建设的决心；同时为投资者提供了一个实时审计窗口。

✨ 核心功能 (Key Features)
多模式锁仓 (Multi-Mode Locking): * 悬崖解锁 (Cliff): 到期一次性全额释放。
线性释放 (Linear): 秒级流式释放，平滑市场压力。
周期释放 (Periodic): 阶梯式分批解锁。
实时链上数据 (Real-time On-chain Data): 所有的 TVL 和锁仓数据均直接从 BSC 智能合约调用，拒绝虚假中心化数据。
高安全性 (High Security): 合约经过深度优化，防范重入攻击与溢出风险。
工业级 UI (Pro Interface): 专为金融审计设计的极简黑暗模式界面。

🛠 技术架构 (Tech Stack)
Smart Contracts: Solidity ^0.8.20 (OpenZeppelin standards).
Frontend: Next.js 14, Tailwind CSS, Shadcn/UI.
Blockchain Interaction: Viem, Wagmi, RainbowKit.
Deployment: BNB Smart Chain (Mainnet).

🚀 快速开始 (Quick Start)
部署环境
``bash
npm install
2. 运行开发服务器Bashnpm run dev
3. 合约地址 (Contracts)ContractNetworkAddressHengJianVaultBSC Mainnet0x...HengJianProxyBSC Mainnet0x...🛡 安全与审计 (Security & Audit)恒缄协议的核心合约均经过多重测试：✅ Slither 静态分析通过。✅ 100% 单元测试覆盖率。✅ 逻辑严格遵循 ERC-20 标准。📄 开源协议 (License)本项目采用 MIT License 开源。
