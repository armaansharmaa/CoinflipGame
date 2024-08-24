
---

# CoinFlip Blockchain Game

A decentralized coinflip game built on blockchain, allowing users to connect their wallets, wager tokens, and play for a chance to win double their tokens back. This project supports multiple blockchains, including Ethereum, Polygon, Solana, and Bitcoin, using their respective testnets/devnets.

## Live Demo

Try the live version: [CoinFlip Game](https://your-vercel-url.vercel.app)

## Features

- **Blockchain Integration**: Supports Ethereum, Polygon, Solana, and Bitcoin testnets/devnets.
- **Wallet Connectivity**: Users can connect their crypto wallets (e.g., MetaMask, Phantom).
- **Wagering & Betting**: Users choose the amount of tokens they want to wager and select either heads or tails.
- **Win or Lose**: If the user guesses the correct side of the coin, they receive double the wagered tokens. If not, they lose their wager.
- **Responsive UI/UX**: Built with **Chakra UI** for a clean, responsive, and accessible design.

## Technologies Used

- **Frontend**: React.js and Next.js
- **Blockchain Libraries**: 
  - Web3.js or Ethers.js for Ethereum/Polygon
  - Solana Web3.js
  - Bitcoin libraries for testnet
- **Wallet Integration**: 
  - MetaMask (Ethereum/Polygon)
  - Phantom (Solana)
  - Bitcoin testnet wallet
- **Smart Contracts**: Deployed on respective testnets/devnets
- **UI/UX**: **Chakra UI** for styling, layout, and responsive design
- **Deployment**: Vercel

## Installation & Setup

### Prerequisites

- Node.js (v14+)
- Yarn or npm
- Crypto Wallet (MetaMask, Phantom, etc.)
  
### Steps to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/armaansharmaa/CoinflipGame.git
cd CoinflipGame
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and visit `http://localhost:3000`.

### Deployment

1. Push the repository to GitHub.
2. Deploy via Vercel.
3. Access the live site on the Vercel deployment URL.

## Usage

1. **Connect Wallet**: Click the "Connect Wallet" button and choose your wallet.
2. **Choose Blockchain**: Select from Ethereum, Polygon, Solana, or Bitcoin.
3. **Place Bet**: Select your wager and choose either heads or tails.
4. **Flip the Coin**: Click "Flip" and wait for the outcome.
5. **Result**: If the result matches your selection, you will receive double the tokens back in your wallet. If not, you lose your wager.

## Testing & Development

- Use respective testnets:
  - **Ethereum**: Rinkeby testnet
  - **Polygon**: Mumbai testnet
  - **Solana**: Devnet
  - **Bitcoin**: Bitcoin Testnet
- Ensure wallet connections and transactions are tested before deploying.

## Future Enhancements

- Add support for more blockchain networks.
- Improve UI animations and user feedback.
- Introduce smart contract security audits.
- Implement advanced game mechanics like staking and jackpot.

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues, please contact [Armaan Sharma](mailto:armaan.sh03@gmail.com).

---