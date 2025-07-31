# 🚀 ChainWatch [📚 Documentation](./docs) • [🐛 Report Bug](https://github.com/harshendram/ChainWatch---Blockchain-powered-monitoring/issues) • [💡 Request Feature](https://github.com/harshendram/ChainWatch---Blockchain-powered-monitoring/issues)

<div align="center">

![ChainWatch Logo](./screenshots/logo.png)

**A decentralized, blockchain-powered uptime monitoring platform built for the future of web services**

[![Built with Next.js](https://img.shields.io/badge/Built%20with-Next.js-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Powered by Bun](https://img.shields.io/badge/Powered%20by-Bun-FF6B6B?style=for-the-badge&logo=bun)](https://bun.sh/)
[![Database](https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql)](https://postgresql.org/)
[![Blockchain](https://img.shields.io/badge/Blockchain-Solana-9945FF?style=for-the-badge&logo=solana)](https://solana.com/)
[![Monorepo](https://img.shields.io/badge/Monorepo-TurboRepo-EF4444?style=for-the-badge&logo=turborepo)](https://turbo.build/)

[📚 Documentation](./docs) • [� Why Twitter Shows Down](./WHY-TWITTER-IS-DOWN.md) • [�🐛 Report Bug](https://github.com/harshendram/ChainWatch---Blockchain-powered-monitoring/issues) • [💡 Request Feature](https://github.com/harshendram/ChainWatch---Blockchain-powered-monitoring/issues)

</div>

---

## 🌟 Overview

ChainWatch revolutionizes website monitoring by leveraging a **decentralized network of validators** to provide unbiased, transparent, and incentivized uptime monitoring. Built with cutting-edge technologies and powered by the Solana blockchain, it ensures your services are monitored 24/7 by a distributed network you can trust.

### ✨ Key Features

<div align="center">

| 🔗 **Decentralized** | 🏆 **Incentivized** | ⚡ **Real-time** | 🔒 **Transparent** |
|:---:|:---:|:---:|:---:|
| Network of validators across the globe | Validators earn rewards for accurate monitoring | Instant alerts and live dashboards | Blockchain-verified monitoring results |

</div>

---

## 🎯 What Makes ChainWatch Special?

### 🌐 **Decentralized Monitoring Network**
Unlike traditional monitoring services that rely on centralized infrastructure, ChainWatch uses a **distributed network of validators** to monitor your websites. This eliminates single points of failure and provides more accurate, geographically diverse monitoring.

### 💰 **Crypto-Economic Incentives**
Validators are **economically incentivized** to provide accurate monitoring data through a token-based reward system built on Solana, ensuring high-quality service and network reliability.

### 🔍 **Transparent & Verifiable**
All monitoring data is **cryptographically verified** and stored on-chain, providing complete transparency and auditability of your website's uptime history.

---

## 📸 Screenshots

<div align="center">

### 🏠 Landing Page
![Landing Page](./screenshots/website-demo.png)
*Beautiful, responsive landing page with dark/light mode support*

### 📊 Dashboard & Architecture
![Dashboard](./screenshots/architecture.png)
*Comprehensive monitoring dashboard with real-time metrics*

### 🚨 Twitter/X Monitoring Challenge
![Twitter Down Issue](./screenshots/whyitshowstwitterdown.png)
*Understanding why social media platforms appear "down" due to anti-bot protection*

</div>

---

## 🏗️ Architecture

ChainWatch is built as a **modern monorepo** with clear separation of concerns:

```
🏢 chainwatch/
├── 📱 apps/                    # Applications
│   ├── 🌐 frontend/           # Next.js 15 + React 19 frontend
│   ├── 🔌 api/                # Express.js backend API
│   ├── 🔍 hub/                # Validator coordination hub
│   └── ✅ validator/          # Validator node implementation
├── 📦 packages/               # Shared packages
│   ├── 🗄️ db/                 # Prisma database layer
│   ├── 🔗 common/             # Shared utilities & types
│   ├── 🎨 ui/                 # Reusable UI components
│   ├── ⚙️ eslint-config/      # ESLint configurations
│   └── 📝 typescript-config/  # TypeScript configurations
└── 📷 screenshots/           # Project screenshots
```

### 🛠️ Technology Stack

<div align="center">

| **Frontend** | **Backend** | **Database** | **Blockchain** | **Infrastructure** |
|:---:|:---:|:---:|:---:|:---:|
| ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) | ![Express](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) | ![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white) | ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) |
| ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) | ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white) | ![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=Prisma&logoColor=white) | ![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=flat-square&logo=web3.js&logoColor=white) | ![TurboRepo](https://img.shields.io/badge/TurboRepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) |
| ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) | ![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=JSON%20web%20tokens) | | | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | ![CORS](https://img.shields.io/badge/CORS-Enabled-green?style=flat-square) | | | |

</div>

---

## � Understanding Twitter/X Monitoring Challenges

### 🎯 **Why Twitter/X Shows as "Down"**

When ChainWatch monitors Twitter/X (twitter.com or x.com), it frequently shows as "DOWN" or unreachable. This isn't because Twitter is actually down, but due to **sophisticated anti-bot and browser-specific restrictions** implemented by X/Twitter.

### 🔒 **X/Twitter's Protection Mechanisms**

#### 🛡️ **Advanced Bot Detection**
X/Twitter has implemented multiple layers of protection:
- **Browser Fingerprinting**: Detects User Agent, JavaScript execution, WebGL signatures
- **Bot Detection Systems**: Identifies headless browsers, automated tools, and non-human patterns
- **Specific Browser Requirements**: Only allows Chrome, Firefox, Safari, Edge with full JavaScript
- **Blocks All Automated Tools**: Postman, curl, wget, Python requests, Node.js fetch

#### 📡 **Why Monitoring Tools Fail**
```bash
# This will fail:
curl -I https://twitter.com
# Response: 403 Forbidden or Connection Reset

# Postman Request to twitter.com:
# Result: "Could not get any response" or "403 Forbidden"
```

**Reason**: X blocks all non-browser HTTP clients and requires:
- Full JavaScript execution environment
- Browser-specific fingerprints and headers
- Human-like interaction patterns
- Real browser rendering capabilities

### 🔧 **Technical Challenges**

#### ❌ **Why Standard Monitoring Fails**
```typescript
// ChainWatch's standard monitoring approach:
async function checkWebsite(url: string) {
  try {
    const response = await fetch(url, { method: 'HEAD', timeout: 5000 });
    return response.ok ? 'UP' : 'DOWN';
  } catch (error) {
    return 'DOWN'; // X/Twitter blocks this immediately
  }
}
```

**Issues with X/Twitter:**
1. **No Browser Context**: Simple HTTP requests lack browser fingerprints
2. **Missing JavaScript**: X requires full browser JavaScript execution
3. **Bot Detection**: Automated requests are immediately flagged
4. **Rate Limiting**: Multiple requests from same IP get blocked
5. **CAPTCHA Challenges**: X serves CAPTCHA to suspicious requests

### 🌐 **Industry Impact**

**Affected Monitoring Services:**
- **Pingdom**: Shows intermittent failures
- **StatusCake**: Cannot reliably monitor  
- **UptimeRobot**: Frequent false positives
- **Site24x7**: Requires browser-based checks

**This affects ALL monitoring services, not just ChainWatch.**

### 💡 **ChainWatch's Approach**

#### 🎯 **Current Status**
- **Expected Behavior**: Twitter/X showing as "DOWN" is normal
- **Not a Bug**: This is X's intended anti-automation protection
- **Industry Standard**: All monitoring services face this challenge

#### 🚀 **Future Enhancements**
ChainWatch's decentralized validator network offers potential solutions:
- **Geographic Distribution**: Validators from different locations
- **Browser Diversity**: Different validators using various methods
- **Human-like Patterns**: Validators mimicking real user behavior
- **Consensus Mechanism**: Multiple validators confirming actual status

#### 📋 **Recommendations**
1. **Alternative Monitoring**: Monitor Twitter's API status page instead
2. **User Education**: Understand that "DOWN" ≠ actually unavailable
3. **Selective Monitoring**: Use different monitoring types for different sites
4. **Browser-Based Validation**: Future validator nodes may use real browsers

### 🎯 **Key Takeaways**

- ✅ **X/Twitter blocks all automated monitoring tools**
- ✅ **This affects ALL monitoring services, not just ChainWatch**
- ✅ **Real browser simulation is the only reliable solution**
- ✅ **This represents the future of web platform protection**

**For ChainWatch Users**: When you see Twitter/X as "DOWN", it likely means the platform is actively blocking monitoring attempts, not that the service is actually unavailable to real users.

---

## �🚀 Quick Start

### 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** 18+ (Required for the project)
- **Bun** 1.2.2+ (Package manager and runtime)
- **PostgreSQL** (Database)
- **Git** (Version control)

### ⚡ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/harshendram/ChainWatch---Blockchain-powered-monitoring.git
   cd ChainWatch---Blockchain-powered-monitoring
   ```

2. **Install dependencies**
   ```bash
   bun install
   ```

3. **Set up environment variables**
   ```bash
   # Copy environment template
   cp .env.example .env
   
   # Configure your environment variables
   # DATABASE_URL=postgresql://username:password@localhost:5432/chainwatch
   # NEXTAUTH_SECRET=your-secret-key
   # SOLANA_RPC_URL=https://api.mainnet-beta.solana.com
   ```

4. **Set up the database**
   ```bash
   # Generate Prisma client
   bun run db:generate
   
   # Run migrations
   bun run db:migrate
   
   # Seed the database (optional)
   bun run db:seed
   ```

5. **Start development servers**
   ```bash
   # Start all services in development mode
   bun run dev
   ```

### 🌐 Access the Application

- **Frontend**: http://localhost:3000
- **API**: http://localhost:8000
- **Database Studio**: `bun run db:studio`

---

## 📖 Detailed Setup

### 🗄️ Database Configuration

The project uses **PostgreSQL** with **Prisma ORM**. The database schema includes:

- **Users**: User authentication and management
- **Websites**: Monitored website configurations
- **Validators**: Network validator nodes
- **WebsiteTicks**: Monitoring data points with status and latency

### 🔐 Authentication

The platform integrates with **Clerk** for user authentication, supporting:
- Email/password authentication
- OAuth providers (Google, GitHub, etc.)
- JWT token-based API authentication

### ⚡ Validator Network

Validators are independent nodes that:
- Monitor assigned websites at regular intervals
- Report status (Good/Bad) and latency metrics
- Earn rewards for accurate monitoring
- Are distributed globally for comprehensive coverage

---

## 🛠️ Available Scripts

```bash
# Development
bun run dev          # Start all development servers
bun run dev:frontend # Start only frontend
bun run dev:api      # Start only API
bun run dev:hub      # Start validator hub
bun run dev:validator # Start validator node

# Building
bun run build        # Build all applications
bun run build:frontend # Build frontend only
bun run build:api    # Build API only

# Database
bun run db:generate  # Generate Prisma client
bun run db:migrate   # Run database migrations
bun run db:seed      # Seed database with test data
bun run db:studio    # Open Prisma Studio
bun run db:reset     # Reset database

# Code Quality
bun run lint         # Lint all packages
bun run format       # Format code with Prettier
bun run check-types  # TypeScript type checking

# Testing
bun run test         # Run all tests
bun run test:e2e     # Run end-to-end tests
```

---

## 🏗️ Project Structure Deep Dive

### 📱 Applications (`apps/`)

#### 🌐 Frontend (`apps/frontend/`)
- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS with dark/light mode
- **UI Components**: Radix UI + shadcn/ui
- **State Management**: React hooks + Context API
- **Authentication**: Clerk integration

#### 🔌 API (`apps/api/`)
- **Framework**: Express.js with TypeScript
- **Database**: Prisma ORM with PostgreSQL
- **Authentication**: JWT middleware
- **Blockchain**: Solana Web3.js integration
- **Features**: RESTful API endpoints for monitoring

#### 🔍 Hub (`apps/hub/`)
- **Purpose**: Coordinate validator network
- **Features**: Validator registration, task distribution
- **Technology**: Node.js with TypeScript

#### ✅ Validator (`apps/validator/`)
- **Purpose**: Individual monitoring nodes
- **Features**: Website monitoring, reporting
- **Technology**: Lightweight Node.js application

### 📦 Packages (`packages/`)

#### 🗄️ Database (`packages/db/`)
- **ORM**: Prisma with PostgreSQL
- **Migrations**: Version-controlled schema changes
- **Seeding**: Test data generation
- **Types**: Auto-generated TypeScript types

#### 🔗 Common (`packages/common/`)
- **Utilities**: Shared helper functions
- **Types**: Common TypeScript interfaces
- **Constants**: Application-wide constants

#### 🎨 UI (`packages/ui/`)
- **Components**: Reusable React components
- **Design System**: Consistent styling
- **Theming**: Dark/light mode support

---

## 🌍 Deployment

### 🔄 CI/CD Pipeline

The project uses **GitHub Actions** for continuous integration:

```yaml
# .github/workflows/ci.yml
- Automated testing on pull requests
- Type checking across all packages
- Linting and formatting validation
- Build verification
```

### 🚀 Production Deployment

#### Frontend (Vercel)
```bash
# Automatic deployment from main branch
vercel --prod
```

#### API (Railway/Heroku)
```bash
# Build and deploy API
bun run build:api
# Deploy to your preferred platform
```

#### Database (Supabase/Neon)
```bash
# Run production migrations
bunx prisma migrate deploy
```

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 🐛 Reporting Bugs

1. **Search existing issues** to avoid duplicates
2. **Use the bug report template** when creating new issues
3. **Include detailed information**: OS, browser, steps to reproduce

### ✨ Requesting Features

1. **Check the roadmap** to see if it's already planned
2. **Use the feature request template**
3. **Provide detailed use cases** and implementation ideas

### 💻 Code Contributions

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Follow the coding standards**: Run `bun run lint` and `bun run format`
4. **Write tests** for new functionality
5. **Create a pull request** with a clear description

### 📝 Coding Standards

- **TypeScript**: Strict mode enabled
- **ESLint**: Extended configurations for React and Node.js
- **Prettier**: Consistent code formatting
- **Commit Convention**: Use conventional commits format

---

## 🗺️ Roadmap

### 🎯 Phase 1: Core Platform (Q1 2024) ✅
- [x] Basic uptime monitoring
- [x] User authentication
- [x] Dashboard interface
- [x] Validator network foundation

### 🚀 Phase 2: Advanced Features (Q2 2024) 🔄
- [ ] Multi-region monitoring
- [ ] Custom alert rules
- [ ] Performance metrics
- [ ] Mobile app

### 🌐 Phase 3: Decentralization (Q3 2024) 📋
- [ ] Token economics implementation
- [ ] Validator staking mechanism
- [ ] Governance system
- [ ] Community rewards

### 🔮 Phase 4: Enterprise (Q4 2024) 💭
- [ ] Enterprise dashboard
<details>
<summary><strong>Why Twitter/X Shows as "Down"</strong></summary>

Twitter/X implements sophisticated anti-bot protection that blocks automated monitoring tools. This affects ALL monitoring services, not just ChainWatch.

**Why this happens:**
- X only allows real browsers with full JavaScript
- Blocks Postman, curl, and automated HTTP requests
- Requires specific browser fingerprints
- Uses advanced bot detection systems

**Solution:** This is expected behavior. See the [Twitter/X Monitoring Challenges](#-understanding-twitterx-monitoring-challenges) section above for detailed technical explanation.
</details>tor Coverage**: Global distribution across 6 continents
- **Data Accuracy**: Blockchain-verified monitoring results

### 📈 Analytics Dashboard

Track your website's performance with:
- **Real-time status updates**
- **Historical uptime charts**
- **Latency trends**
- **Geographical monitoring distribution**

---

## 🔒 Security

### 🛡️ Security Measures

- **JWT Authentication**: Secure API access
- **Rate Limiting**: Protection against abuse
- **Input Validation**: Sanitized user inputs
- **CORS Configuration**: Controlled cross-origin requests
- **Environment Variables**: Secure configuration management

### 🔐 Data Privacy

- **Minimal Data Collection**: Only necessary monitoring data
- **Encryption**: Data encrypted in transit and at rest
- **User Control**: Users own their monitoring data
- **Compliance**: GDPR and privacy-by-design principles

---

## 📚 API Documentation

### 🔗 Base URL
```
Production: https://api.chainwatch.com
Development: http://localhost:8000
```

### 🔑 Authentication
```bash
# Include JWT token in headers
Authorization: Bearer <your-jwt-token>
```

### 📋 Endpoints

#### Websites
```bash
# Create a new website
POST /api/v1/website
{
  "url": "https://example.com"
}

# Get website status
GET /api/v1/website/status?websiteId=<id>

# List user websites
GET /api/v1/websites
```

#### Monitoring
```bash
# Get uptime metrics
GET /api/v1/metrics/:websiteId

# Get validator reports
GET /api/v1/reports/:websiteId
```

---

## 🆘 Troubleshooting

### 🐛 Common Issues

<details>
<summary><strong>Database Connection Errors</strong></summary>
### 🐛 Common Issues

<details>
<summary><strong>Why Twitter/X Shows as "Down"</strong></summary>

Twitter/X implements sophisticated anti-bot protection that blocks automated monitoring tools. This affects ALL monitoring services, not just ChainWatch.

**Why this happens:**
- X only allows real browsers with full JavaScript
- Blocks Postman, curl, and automated HTTP requests
- Requires specific browser fingerprints
- Uses advanced bot detection systems

**Solution:** This is expected behavior. Read our [detailed explanation](./WHY-TWITTER-IS-DOWN.md) for technical details.
</details>

<details>
<summary><strong>Database Connection Errors</strong></summary>

# Verify DATABASE_URL in .env
DATABASE_URL=postgresql://user:password@localhost:5432/chainwatch

# Reset database connection
bun run db:generate
```
</details>

<details>
<summary><strong>Bun Installation Issues</strong></summary>

```bash
# Install Bun (macOS/Linux)
curl -fsSL https://bun.sh/install | bash

# Install Bun (Windows)
powershell -c "irm bun.sh/install.ps1 | iex"

# Verify installation
bun --version
```
</details>

<details>
<summary><strong>Port Already in Use</strong></summary>

```bash
# Find process using port
lsof -i :3000
netstat -ano | findstr :3000

# Kill process
kill -9 <PID>
taskkill /PID <PID> /F
```
</details>

---

## 💬 Community & Support

<div align="center">

### 🌟 Join Our Community

[![Discord](https://img.shields.io/badge/Discord-Join%20Chat-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/chainwatch)
[![Twitter](https://img.shields.io/badge/Twitter-Follow%20Us-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/chainwatch)
[![GitHub](https://img.shields.io/badge/GitHub-Star%20Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harshendram/ChainWatch---Blockchain-powered-monitoring)

### 💬 Get Help

- **Documentation**: Comprehensive guides and tutorials
- **GitHub Discussions**: Community Q&A and feature discussions
- **Discord Server**: Real-time community support
- **Email Support**: hello@chainwatch.com

</div>

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 ChainWatch

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software")...
```

---

## 🙏 Acknowledgments

Special thanks to:

- **[Solana Foundation](https://solana.org/)** - For the incredible blockchain infrastructure
- **[Vercel](https://vercel.com/)** - For seamless deployment and hosting
- **[Prisma](https://prisma.io/)** - For the excellent database toolkit
- **[shadcn/ui](https://ui.shadcn.com/)** - For beautiful UI components
- **All Contributors** - For making this project possible

---

<div align="center">

### 🌟 Star the Repository

If you find ChainWatch useful, please consider giving it a star! ⭐

**[⬆ Back to Top](#-chainwatch)**

---

*Built with ❤️ by the ChainWatch team*

[![Made with Bun](https://img.shields.io/badge/Made%20with-Bun-FF6B6B?style=flat-square&logo=bun)](https://bun.sh/)
[![Powered by Solana](https://img.shields.io/badge/Powered%20by-Solana-9945FF?style=flat-square&logo=solana)](https://solana.com/)

</div>
