# Ardana

AI-Powered On-Chain Investment Platform for Effortless DeFi Growth.

## ⚠️ Problem to Solve.

Managing DeFi investments is still too complex for most users. Even experienced crypto holders struggle to decide where to allocate assets — lending, staking, liquidity provision, yield farming or governance staking — across dozens of protocols and chains.

Tracking yields, understanding risks and optimizing returns require constant monitoring, gas spending and manual execution. Users often end up leaving idle stablecoins in wallets or spreading assets across platforms without a unified strategy or dashboard.

There’s a need for a personalized, automated and transparent on-chain investment assistant that can analyze wallet assets, recommend optimal DeFi strategies and execute investments securely — all in one interface.

---

## ✅ Possible Solution.

**Ardana** is an AI-powered DeFi investment app that lets users deploy, lock and track assets across protocols effortlessly. When a user connects their wallet, Validus automatically analyzes on-chain balances and offers AI-configured investment strategies tailored to the user’s risk profile, goals, and token holdings. Users can choose to:

- Follow AI Recommendations: Auto-invest in strategies like lending, staking, and liquidity provision for optimized yield.
- Self-Manage Investments: Manually allocate assets across DeFi pools and track all investments in one dashboard.

Once funds are locked, Ardana manages compounding, rebalancing and reinvestment automatically. Users can simply “set it and forget it,” returning later to see their capital working on-chain. It also includes some core features like:
- **AI Strategy Engine:** Analyzes wallet portfolio and market conditions to suggest personalized investment allocations.
- **Unified On-Chain Dashboard:** View and manage all DeFi positions (lending, staking, LPs, vaults) in one place.
- **Smart Locking System:** Allow users to lock funds for chosen periods in AI-generated yield strategies.
- **Cross-Protocol Integration:** Interact with lending, DEX, and staking protocols (Aave, Compound, Lido, Raydium, etc.).
- **Yield & Risk Analytics:** View real-time yield rates, APYs, and risk breakdowns per strategy.
- **Auto-Rebalancing:** Adjust allocations dynamically based on changing market conditions.
- **Portfolio Tracking:** Track wallet balance growth, investment performance, and transaction history seamlessly.
- **Gas & Fee Optimization:** Aggregate on-chain operations to minimize transaction costs.

---

## ⚙️ Architecture.

![Working Architecture](./)
[Excalidaw File...](./)

---

## 🛠 Tools, Languages & Frameworks used.

- **ReactJS:** Frontend library for creating interactive dashboards and real-time portfolio tracking.
- **TypeScript:** For strong typing and cleaner code across frontend and backend.
- **Node.js:** Backend runtime environment to handle strategy computation, API calls, and protocol integrations.
- **Express.js:** Framework for building RESTful APIs for wallet connections, investments, and yield tracking.
- **Solidity / Rust:** Smart contract languages for creating asset vaults, staking mechanisms, and automated strategies.
- **Web3.js / Ethers.js:** Libraries for interacting with EVM-based blockchains.
- **Solana Web3.js (optional):** For cross-chain DeFi strategy expansion.
- **OpenAI API / ML Engine:** Powers the AI strategy recommendation system.
- **PostgreSQL / MongoDB:** Databases for storing user portfolios, yield history, and analytics data.
- **Redis:** Used for caching and real-time updates of APY and protocol data.
- **IPFS:** For decentralized storage of strategy metadata and reports.
- **DeFi Protocol SDKs:** Aave, Compound, Lido, Uniswap, Raydium and others for live integrations.

---

## 📂 Folder Structure.

- **client:** Contains the frontend codebase.
- **server:** Contains the backend code and blockchain integration logic.

---

## 🧑‍💻 Contributions to this repo are WELCOME.👋

- 🎨 Any improvements to the design and UI are welcome.
- 🔨 Try to break the website by testing it to find any bugs. If you find any, check if there is an issue already open for it, if there is none, then report it.

---

## 🔃 Steps to be followed in order to make valid contributions to this repo.

**1.** Fork the [Ardana](https://github.com/mrinnnmoy/Ardana) repo by clicking on the fork button on the top of the page. This will create a copy of this repository in your account.

**2.** Clone the forked repository

        git clone "https://github.com/<your-github-username>/Ardana"

- Download and install Node JS v16.16.0
- Download and install Git.
- Go to the terminal of your code editor and run "npm install" to download packages.
- Run "npm run dev" to start a local server.

**3.** Make necessary changes and commit those changes. <br />
Remember never push anything to the Main branch. <br />

Always change your branch to "develop" using:

    git checkout develop

Again check your current branch using:

    git branch

It should point \*develop

Now add your changes using:

    git add files-you-edited

If there are multiple files you can use:

    git add .

Now create a commit message using:

    git commit -m "<commit-message-goes-here>"

**4.** Push changes to GitHub

    git push origin develop

**5.** Create a Pull Request 👋<br>

Now you go to your repository on GitHub, you’ll see a `Compare & pull request` button. Click on that button and now write a summary of what changes you have done.( Attach images if required). I will review your code and merge it if it passes all the tests.❤️
