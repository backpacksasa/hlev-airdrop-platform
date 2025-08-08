# HLEV Token Airdrop Platform

A cutting-edge HyperEVM-powered token airdrop platform with advanced blockchain integration and secure claiming mechanisms.

## 🌟 Features

- **Multi-Wallet Support**: MetaMask, OKX, Bitget, Rabby, Binance Web3
- **HyperEVM Integration**: Native support for HyperEVM mainnet (Chain ID 999)
- **EIP-712 Signatures**: Secure structured data signing for claim verification
- **Real-time Validation**: Live HYPE balance checking and eligibility verification
- **Modern UI**: Glassmorphism design with smooth animations and responsive layout
- **Treasury Management**: Secure HYPE transfer system to designated treasury wallet

## 🎯 Eligibility Criteria

### Airdrop Pool Distribution

**Token Holders (65%)**
- $HSTR – Hold ≥ 10,000 tokens
- $LIQD (LiquidLaunch) – Hold ≥ 10,000 tokens

**Community Allocations**
- 20% — Presale Participants
- 15% — Community Holders

### Eligible Communities
- **@LiquidLaunchHL** - $LIQD Holders (≥10k)
- **@HypioHL** - NFT Holders
- **@baldbrothers_** - NFT Holders
- **@Hypaos** - NFT Holders

## 🚀 Technical Architecture

### Core Technologies
- **Frontend**: Vanilla HTML, CSS, JavaScript for maximum performance
- **Blockchain**: HyperEVM mainnet integration via Ethers.js v5.7.2
- **Security**: EIP-712 structured data signing
- **UI/UX**: Modern glassmorphism design with CSS Grid and Flexbox

### Network Configuration
- **Chain ID**: 999 (HyperEVM)
- **RPC URL**: https://rpc.hyperliquid.xyz/evm
- **Native Currency**: HYPE
- **Block Explorer**: https://hyperliquid.cloud.blockscout.com

### Smart Contract Integration
- **Treasury Wallet**: `0xd6e7bf33a21b56d5927bbf0101fe45ff92ecf9ba`
- **Claim Process**: Three-step verification (EIP-712 → HYPE Transfer → HLEV Claim)
- **Minimum Eligibility**: 1 HYPE token required

## 🔧 Setup & Deployment

### Local Development
```bash
# Serve the application locally
python -m http.server 5000 --bind 0.0.0.0
```

### GitHub Pages Deployment
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Set source to main branch
4. Access via: `https://yourusername.github.io/repository-name`

### Replit Deployment
- Already configured for Replit hosting
- Access via provided Replit URL
- Automatic HTTPS and custom domain support

## 🛡️ Security Features

- **EIP-712 Signatures**: Structured data signing prevents replay attacks
- **Gas Optimization**: Smart gas calculation for treasury transfers
- **Error Handling**: Comprehensive error states and user feedback
- **Wallet Validation**: Real-time balance verification before claims

## 🎨 Design System

- **Colors**: Black background (#000000), gradient accents (#4f46e5 to #6366f1)
- **Typography**: Inter font family for clean, modern text
- **Effects**: Glassmorphism with backdrop blur and subtle animations
- **Responsive**: Mobile-first approach with adaptive layouts

## 📱 Wallet Integration

Supports all major Web3 wallets:
- MetaMask (Browser extension & Mobile)
- OKX Wallet
- Bitget Wallet
- Rabby Wallet
- Binance Web3 Wallet

## 🔄 Claim Process

1. **Connect Wallet**: Choose from supported wallet providers
2. **Network Switch**: Automatically switch to HyperEVM mainnet
3. **Eligibility Check**: Verify HYPE balance and eligibility status
4. **EIP-712 Signature**: Sign structured claim data
5. **Treasury Transfer**: Send HYPE to treasury wallet
6. **Token Claim**: Receive HLEV tokens with confetti celebration

## 📊 Project Structure

```
├── index.html          # Main application file
├── replit.md           # Project documentation and architecture
├── README.md           # This file
└── attached_assets/    # UI mockups and design references
```

## 🚀 Live Demo

Access the live airdrop platform: [Your Deployment URL]

## 🤝 Contributing

This is a production airdrop platform. For security reasons, please reach out before making contributions.

## 📄 License

Private - All rights reserved.

---

**Built with ❤️ for the HyperEVM ecosystem**