# 🌐 Soclynk - Decentralized Social Networking Platform

![Soclynk Logo](/public/soclynk-logo.svg)

Soclynk is a revolutionary decentralized social networking platform built on the Internet Computer blockchain. Connect, share, and engage with others in a secure, transparent, and truly decentralized environment where you have complete control over your data and social interactions.

## ✨ Key Features

### 🔐 Secure Authentication
- Fully decentralized user authentication system
- Self-sovereign identity management
- No central authority controlling your data

### 👤 Profile Management
- Create and customize your digital identity
- Manage your personal information securely
- Build your social presence on the blockchain

### 📱 Social Interactions
- Share posts, thoughts, and media
- Engage with other users through comments and reactions
- Follow interesting profiles and build your network
- Real-time notifications for social activities

### 🏛 Governance System
- Participate in platform governance
- Create and vote on proposals
- Shape the future of the platform
- Community-driven decision making

### 🌍 Community Features
- Create and join communities
- Engage in topic-specific discussions
- Build specialized interest groups
- Community moderation tools

## 🛠 Technology Stack

### Frontend
- **React 18+**: Modern UI framework
- **TypeScript**: Type-safe development
- **Tailwind CSS**: Utility-first styling
- **Vite**: Next-generation frontend tooling

### Backend
- **Rust**: Systems programming language
- **Internet Computer (IC)**: Blockchain platform
- **Canister Smart Contracts**: Decentralized backend logic

### Development Tools
- **DFX**: Internet Computer SDK
- **WSL** (Windows Subsystem for Linux): Linux development on Windows
- **Development Environment**: Cross-platform support

## 🚀 Getting Started

### Prerequisites
1. Install Node.js (v16 or higher)
2. Install DFX (Internet Computer SDK)
3. Install Rust and Cargo
4. (Windows users) Install WSL2

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/soclynk.git
   cd soclynk
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development environment:
   - Windows users:
     ```bash
     .\start-local-dev.bat
     ```
   - Unix/Mac users:
     ```bash
     ./start-dev.sh
     ```

4. Connect the backend:
   ```bash
   .\connect-backend.bat
   ```

5. Access the application:
   - Open your browser and navigate to http://localhost:5173
   - The frontend should now be connected to the local backend

## 🔧 Troubleshooting

### Backend Connection Issues
If you experience problems connecting to the backend:

1. For general connection issues:
   ```bash
   .\fix-backend.bat
   ```

2. For WSL-specific issues:
   ```bash
   .\fix-backend-wsl.bat
   ```

3. Common solutions:
   - Ensure DFX is running correctly
   - Check if the correct ports are available
   - Verify WSL is properly configured (Windows users)

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

Need help? Here are your options:

- Create an issue in the GitHub repository
- Join our community Discord server
- Check our documentation
- Contact the development team

## 🔮 Future Roadmap

- [ ] Mobile application development
- [ ] Enhanced privacy features
- [ ] Cross-chain integration
- [ ] Advanced content monetization
- [ ] AI-powered content recommendations
