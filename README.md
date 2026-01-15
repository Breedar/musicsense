## What is MusicSense?

MusicSense is an innovative platform designed for music bloggers, journalists, playlist curators, and content creators who need to produce high-quality music content at scale. Powered by advanced AI and built on Stellar blockchain, it transforms how you analyze songs, understand artists, and create engaging narratives around music.

Whether you're writing album reviews, creating Spotify playlist descriptions, or building artist profiles for your music blog, MusicSense gives you the tools to work smarter and produce content that resonates.

## What MusicSense Offers

### **Deep Lyric Analysis**

Go beyond surface-level interpretations. Our AI engine dissects song lyrics to reveal:

- **Thematic Exploration**: Identify recurring themes, metaphors, and symbolic meanings
- **Emotional Mapping**: Understand the emotional journey throughout the song
- **Cultural Context**: Discover historical and cultural references embedded in lyrics
- **Literary Techniques**: Analyze rhyme schemes, wordplay, and poetic devices
- **Multiple Perspectives**: Generate different interpretations based on context
- **Comparative Analysis**: Compare themes across songs, albums, or artists

### **Professional Biography Generator**

Create compelling, publication-ready artist biographies in minutes:

- **Career Milestones**: Automatically structured chronological narratives
- **Style Adaptation**: Choose from different tones (journalistic, promotional, academic, casual)
- **Length Variants**: Generate short bios, medium profiles, or comprehensive features
- **Influence Mapping**: Highlight musical influences and genre evolution
- **Achievement Highlighting**: Emphasize awards, chart performance, and cultural impact
- **Customizable Focus**: Emphasize different aspects (discography, personal story, impact)

### **Content Dashboard**

Manage all your music content projects efficiently:

- **Project Organization**: Group analyses by artist, album, genre, or publication
- **Version Control**: Track edits and maintain multiple drafts
- **Collaboration Tools**: Share projects with team members
- **Export Options**: Download in Markdown, HTML, or plain text
- **Search & Filter**: Quickly find past analyses and biographies
- **Template Library**: Save and reuse content structures

### **Creative Tools Suite**

- **Playlist Description Generator**: Create engaging descriptions for streaming playlists
- **Social Media Snippets**: Generate shareable quotes and insights from analyses
- **Album Review Frameworks**: Structured templates for comprehensive reviews
- **Song Story Creator**: Craft narratives around song creation and meaning
- **Mood & Vibe Tags**: AI-generated descriptive tags for content categorization

## 🔗 Stellar Blockchain: Powering the Future of Music Content

MusicSense leverages Stellar's blockchain technology to create a fair, transparent ecosystem for music content creators and artists:

### **Why Stellar for Music Content?**

**Content Ownership & Rights**
- Every piece of content you create is timestamped and verified on Stellar's blockchain
- Establish provable authorship for your analyses and articles
- Protect your intellectual property with immutable records
- Create portable credentials showcasing your work across platforms

**Tokenized Content Marketplace**
- Sell premium lyric analyses and artist biographies as digital assets
- Artists can purchase verified biographical content directly from creators
- Create subscription tokens for exclusive access to your content library
- Micropayments for individual analyses using Stellar's low-fee infrastructure

**Creator Monetization**
- Accept payments in XLM, USDC, or custom tokens for your content
- Instant settlements with near-zero transaction fees (< $0.01)
- No intermediary payment processors taking 3-5% cuts
- Enable global payments without currency conversion hassles

**Artist-Creator Collaboration**
- Artists can commission authorized biographies through smart contracts
- Automatic royalty splits when content is licensed or resold
- Transparent payment tracking for collaborative projects
- Escrow functionality for commissioned work

**Reputation System**
- Build an on-chain portfolio of verified music content
- Earn reputation tokens for quality contributions
- Provable track record for pitching to publications
- Decentralized review system for content quality

**Global Creator Network**
- Connect with music journalists and creators worldwide
- Participate in decentralized content syndicates
- Cross-border payments without banking infrastructure
- Support creators in emerging markets

### **Stellar Integration Benefits**

1. **Micropayment Viability**: Pay-per-analysis models become profitable with Stellar's low fees
2. **Fast Transactions**: Content purchases settle in 3-5 seconds, not days
3. **Programmable Payments**: Smart contracts automate revenue sharing and licensing
4. **Asset Tokenization**: Turn your content library into tradeable digital assets
5. **Financial Inclusion**: Enable creators worldwide to monetize without traditional banking

### **How It Strengthens Stellar Ecosystem**

- **Content Creator Onboarding**: Brings music industry professionals onto Stellar network
- **Use Case Diversity**: Demonstrates blockchain utility beyond finance
- **Transaction Volume**: Regular micropayments increase network activity
- **Token Economy**: Creates demand for XLM and stablecoins through content marketplace
- **Developer Blueprint**: Open-source reference for content-focused dApps on Stellar

## Built With

### **Frontend Stack**
```
Next.js 14 (App Router)    →  Server-side rendering & optimal performance
TypeScript                  →  Type-safe code and better developer experience
Tailwind CSS                →  Rapid, responsive UI development
Framer Motion              →  Smooth animations and transitions
Zustand                    →  Lightweight state management
React Query                →  Server state management
Shadcn/ui                  →  Beautiful, accessible components
Stellar SDK                →  Blockchain wallet integration
```

### **Backend Architecture**
```
NestJS                     →  Scalable, enterprise-grade backend
TypeScript                 →  End-to-end type safety
PostgreSQL                 →  Robust relational database
TypeORM                    →  Type-safe database operations
OpenAI API                 →  Advanced AI lyric analysis
Anthropic Claude API       →  Natural language biography generation
Redis                      →  Caching and session management
Bull Queue                 →  Background job processing
Stellar Node.js SDK        →  Blockchain transactions
Passport.js                →  Authentication strategies
```

### **Blockchain Layer**
```
Stellar Network            →  Payment rails and asset tokenization
Soroban Smart Contracts    →  Programmable content licensing (coming soon)
Horizon API                →  Transaction queries and account management
Freighter Wallet           →  User wallet integration
SEP-24 Anchors             →  Fiat on/off ramp integration
```

### **AI & Machine Learning**
```
OpenAI GPT-4              →  Deep lyric interpretation
Claude 3.5 Sonnet         →  Biography generation and content creation
LangChain                 →  LLM orchestration and prompt engineering
Vector Database (Pinecone) →  Semantic search across analyses
```

## Quick Start

### Prerequisites

Make sure you have these installed:
- **Node.js** 18.x or higher
- **PostgreSQL** 14+
- **Redis** 6+ (optional but recommended)
- **OpenAI API Key** (for lyric analysis)
- **Anthropic API Key** (for biography generation)
- **Stellar Account** (testnet for development)

### Step 1: Clone & Install

```bash
# Clone the repository
git clone https://github.com/yourusername/musicsense.git
cd musicsense

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

### Step 2: Configure Environment

**Frontend Environment** (`frontend/.env.local`):
```bash
NEXT_PUBLIC_API_URL=http://localhost:4000
NEXT_PUBLIC_STELLAR_NETWORK=testnet
NEXT_PUBLIC_HORIZON_URL=https://horizon-testnet.stellar.org
NEXT_PUBLIC_FREIGHTER_ENABLED=true
```

**Backend Environment** (`backend/.env`):
```bash
# Database
DATABASE_URL=postgresql://user:password@localhost:5432/musicsense
DB_HOST=localhost
DB_PORT=5432
DB_USERNAME=postgres
DB_PASSWORD=yourpassword
DB_DATABASE=musicsense

# Authentication
JWT_SECRET=your-super-secure-jwt-secret
JWT_EXPIRES_IN=30d

# AI Services
OPENAI_API_KEY=sk-your-openai-key
ANTHROPIC_API_KEY=sk-ant-your-anthropic-key

# Stellar Configuration
STELLAR_NETWORK=testnet
STELLAR_HORIZON_URL=https://horizon-testnet.stellar.org
STELLAR_PLATFORM_SECRET=YOUR_STELLAR_SECRET_KEY
STELLAR_PLATFORM_PUBLIC=YOUR_STELLAR_PUBLIC_KEY

# Redis (Optional)
REDIS_HOST=localhost
REDIS_PORT=6379
REDIS_PASSWORD=

# Content Storage
CLOUDINARY_URL=cloudinary://api_key:api_secret@cloud_name
```

### Step 3: Database Setup

```bash
cd backend

# Run migrations
npm run migration:run

# Seed initial data (optional)
npm run seed
```

### Step 4: Launch Application

**Terminal 1** - Backend:
```bash
cd backend
npm run start:dev
# Server runs on http://localhost:4000
```

**Terminal 2** - Frontend:
```bash
cd frontend
npm run dev
# App runs on http://localhost:3000
```

### Step 5: Create Your First Analysis

1. Navigate to `http://localhost:3000`
2. Sign up for an account
3. Connect your Freighter wallet (optional, for blockchain features)
4. Paste song lyrics and generate your first analysis!

## Usage Examples

### Analyzing Song Lyrics

```typescript
// API Example: Analyze a song
POST /api/lyrics/analyze

{
  "lyrics": "Your song lyrics here...",
  "artistName": "Artist Name",
  "songTitle": "Song Title",
  "analysisDepth": "comprehensive", // or "quick", "detailed"
  "focusAreas": ["themes", "metaphors", "emotions"]
}

// Response includes:
// - Thematic breakdown
// - Emotional arc
// - Literary devices
// - Cultural context
// - Multiple interpretations
```

### Generating Artist Biographies

```typescript
// API Example: Generate biography
POST /api/biographies/generate

{
  "artistName": "Artist Name",
  "style": "journalistic", // or "promotional", "academic", "casual"
  "length": "medium", // or "short", "long"
  "focusAreas": ["career", "influences", "impact"],
  "includeDiscography": true
}
```

### Stellar Payment Integration

```typescript
// Purchase premium content with Stellar
import { purchaseContent } from '@/lib/stellar';

const transaction = await purchaseContent({
  contentId: "analysis-123",
  priceInXLM: 5,
  buyerPublicKey: userWallet.publicKey
});

// Content unlocked instantly after blockchain confirmation
```

## Testing

```bash
# Frontend tests
cd frontend
npm run test              # Run unit tests
npm run test:e2e          # Run end-to-end tests
npm run test:coverage     # Generate coverage report

# Backend tests
cd backend
npm run test              # Unit tests
npm run test:integration  # Integration tests
npm run test:e2e          # End-to-end API tests

# Stellar integration tests
npm run test:stellar      # Blockchain functionality tests
```

## API Documentation

Once your backend is running, explore the full API documentation at:
- **Swagger UI**: `http://localhost:4000/api/docs`
- **OpenAPI JSON**: `http://localhost:4000/api/docs-json`

Key endpoints:
- `POST /api/lyrics/analyze` - Analyze song lyrics
- `POST /api/biographies/generate` - Generate artist biographies
- `GET /api/content/:id` - Retrieve saved content
- `POST /api/payments/stellar` - Process Stellar payments
- `GET /api/marketplace` - Browse content marketplace

## Contributing

We'd love your help making MusicSense better! Here's how to contribute:

### Ways to Contribute

- **Bug Reports**: Found a bug? Open an issue with details
- **Feature Requests**: Have an idea? We want to hear it
- **Documentation**: Help improve our docs
- **Testing**: Write tests or improve test coverage
- **Code**: Submit pull requests for new features or fixes

### Development Workflow

```bash
# 1. Fork and clone
git clone https://github.com/your-username/musicsense.git

# 2. Create feature branch
git checkout -b feature/your-feature-name

# 3. Make your changes and commit
git commit -m "Add: your feature description"

# 4. Push and create PR
git push origin feature/your-feature-name
```

### Code Standards

- Follow TypeScript best practices
- Write meaningful commit messages
- Add tests for new features
- Update documentation as needed
- Run linter before committing: `npm run lint`
