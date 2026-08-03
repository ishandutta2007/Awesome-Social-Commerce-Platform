# Awesome-Social-Commerce-Platform

## Similar Projects to Social Commerce Platforms

**Social Commerce Platforms** enable shopping experiences driven by social interactions — influencer storefronts, affiliate links, live shopping/livestream commerce, shoppable video, comment-based selling, and social discovery. Leading commercial platforms include ShopMy, LTK (LikeToKnow.it), Spring by Amaze, Popshop Live, Whatnot, CommentSold, Firework, Flip.shop, ShopThing, and LiSA.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully featured open-source alternatives that combine influencer networks, live auction/shopping, and social discovery at commercial scale are rare. The strongest options are modern headless e-commerce platforms, live-commerce systems, and marketplace frameworks that can be extended with social and live features.

## 🏢 SaaS / Hosted Platforms

- **[LTK (LikeToKnow.it)](https://www.liketoknow.it/)** — Leading influencer marketing and social commerce platform for creators to share shoppable content and earn commissions.
- **[ShopMy](https://shopmy.us/)** — Influencer storefront and affiliate commerce platform.
- **[Spring by Amaze](https://www.spring.com/)** — Social commerce and creator storefront solution.
- **[Popshop Live](https://www.popshop.live/)** — Live shopping and social commerce platform.
- **[Whatnot](https://www.whatnot.com/)** — Live shopping and auction marketplace popular for collectibles and community-driven commerce.
- **[CommentSold](https://www.commentsold.com/)** — Social selling platform that turns social media comments and live streams into sales (especially strong for Facebook/Instagram selling).
- **[Firework](https://www.firework.com/)** — Shoppable video and live commerce platform.
- **[Flip.shop](https://flip.shop/)**, **[ShopThing](https://www.shopthing.com/)**, **[LiSA](https://lisa.commerce/)** and similar — Specialized social commerce, live shopping, or creator-focused platforms.

## 🔓 Open-Source Software

### Modern Headless / API-First E-Commerce (Best Foundations)
- **[Medusa](https://github.com/medusajs/medusa)** — Extremely popular open-source headless commerce platform (Node.js/TypeScript). Highly extensible — excellent base for building custom social commerce, creator storefronts, or marketplace experiences.
- **[Saleor](https://github.com/saleor/saleor)** — GraphQL-first open-source e-commerce platform. Strong for composable commerce and custom storefronts.
- **[Vendure](https://github.com/vendure-ecommerce/vendure)** — Modern TypeScript headless commerce framework designed for customization and multi-channel selling.
- **[Spree Commerce](https://github.com/spree/spree)** — Mature open-source e-commerce platform with solid marketplace and multi-vendor capabilities.

### Live Shopping & Social Commerce Oriented
- Open-source **live shopping / livestream e-commerce** systems (primarily from Chinese open-source communities, e.g., Wanyue and similar projects). These often include multi-merchant support, live streaming with product showcasing, host/affiliate distribution, and short-video commerce features. Many are fully open-source for learning and non-commercial use, with commercial licenses available.
- Community projects that combine e-commerce backends with WebRTC or third-party live streaming for shoppable live experiences.

### Marketplace & Social Platforms
- Open-source marketplace frameworks (built on Medusa, Saleor, Spree, or custom) that support multi-vendor selling and can be extended with social feeds or creator profiles.
- Self-hosted social network platforms that include marketplace modules (e.g., platforms offering posts + buy/sell listings).

### Supporting Open-Source Building Blocks
- **Live streaming**: Use open-source media servers (e.g., MediaMTX, OvenMediaEngine) or WebRTC solutions together with an e-commerce backend.
- **Affiliate / creator tools**: Custom commission and tracking systems built on top of Medusa/Saleor + a simple creator portal.
- **Shoppable video**: Combine video players with product hotspots using open-source frontends.

### Typical Open-Source Approach
1. **Commerce engine** — Medusa, Saleor, or Vendure
2. **Storefront / creator shops** — Next.js, Remix, or custom React/Vue frontends
3. **Live features** — Integrate open-source or self-hosted live streaming + real-time chat
4. **Social layer** — Activity feeds, follows, and content modules (or integrate with ActivityPub/Mastodon-style networks)
5. **Payments & affiliates** — Stripe Connect or similar for multi-party payouts

This stack gives full ownership of customer data, no platform commissions on sales, and the flexibility to build influencer, live, or community-driven commerce experiences.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to social commerce, live shopping, creator storefronts, or headless e-commerce that can support social selling.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open commerce tools empower creators and merchants to own their social shopping experiences! 🛍️
