---
name: browse
description: "Playbook MCP library index: list every playbook, find the right one for a task and load it. Use when the user types /playbook:browse, asks which playbooks exist, or asks for a playbook on a topic without naming one."
---

# Playbook library

1. Call the Playbook MCP `list_playbooks` tool for the live list (it also shows which ones this license owns). If it is not connected, use the table below and tell the user: "Connect Playbook MCP (playbookmcp.com) to load playbooks."
2. If the user named a topic, pick the best match (use `search` when unsure) and say which playbook you chose.
3. Load it with `get_section` (start with "3. The method") and follow the method step by step, as its skill describes.
4. With no topic, show the list grouped by area and ask which one to open.

| Skill | MCP slug | Playbook |
|---|---|---|
| /playbook:landing-page | `landing-page-playbook` | Vol. 17 The Landing Page Playbook: Pages that explain, convince and convert |
| /playbook:social-growth | `social-growth-playbook` | Vol. 18 The Social Growth Playbook: A steady, honest way to grow on social |
| /playbook:solo-indie-developer | `solo-indie-developer` | Vol. 19 The Solo Indie Developer Playbook: Scope, ship and sustain games on your own |
| /playbook:ai-codebase | `ai-codebase-playbook` | Vol. 20 The AI Codebase Playbook: Keep AI-written code clean, safe and maintainable |
| /playbook:prompt-systems | `prompt-systems-playbook` | Vol. 21 The Prompt Systems Playbook: Reliable, repeatable results from AI |
| /playbook:realistic-ai-photo | `realistic-ai-photo` | Vol. 22 The Realistic AI Photo Playbook: Believable images, made responsibly |
| /playbook:localization | `localization-playbook` | Vol. 23 The Localization Playbook: Take your app and site to new languages |
| /playbook:digital-product | `digital-product-playbook` | Vol. 24 The Digital Product Playbook: Create, package and sell e-books and guides |
| /playbook:pricing-free-trial | `pricing-free-trial` | Vol. 25 The Pricing & Free Trial Playbook: Price with confidence, convert trials to customers |
| /playbook:customer-acquisition | `customer-acquisition` | Vol. 26 The Customer Acquisition Playbook: Find, reach and win your first 100 customers |
| /playbook:saas-funnel | `saas-funnel-playbook` | Vol. 27 The SaaS Funnel Playbook: Buyer psychology from first visit to paid plan |
| /playbook:google-ads | `google-ads-playbook` | Vol. 28 The Google Ads Playbook: Profitable search campaigns for small budgets |
| /playbook:meta-tiktok-ads | `meta-tiktok-ads-playbook` | Vol. 29 The Meta & Tiktok Ads Playbook: Creative-led paid social that pays back |
| /playbook:app-icon-brand-identity | `app-icon-brand-identity-playbook` | Vol. 30 The App Icon & Brand Identity Playbook: Design an app icon and brand that win store taps in 2026 |
| /playbook:mcp-registry-directory-listing | `mcp-registry-directory-listing-playbook` | Vol. 31 The Mcp Registry & Directory Listing Playbook: Get your MCP server listed, found and installed across every registry |
| /playbook:email-lifecycle | `email-lifecycle-playbook` | Vol. 32 The Email & Lifecycle Playbook: Welcome, nurture, win-back and upgrade sequences |
| /playbook:aaa-game-genai | `aaa-game-genai-playbook` | Vol. 33 The Aaa Game With Generative Ai Playbook: How a small team ships AAA-looking games with AI |
| /playbook:activation-onboarding | `activation-onboarding-playbook` | Vol. 34 The Activation & Onboarding Playbook: Get new users to value in the first session |
| /playbook:analytics-tracking | `analytics-tracking-playbook` | Vol. 35 The Analytics & Tracking Playbook: GA4, events, attribution and dashboards that matter |
| /playbook:retention-churn | `retention-churn-playbook` | Vol. 36 The Retention & Churn Playbook: Keep customers, win them back, grow accounts |
| /playbook:copywriting | `copywriting-playbook` | Vol. 37 The Copywriting Playbook: Words that sell without hype |
| /playbook:product-launch | `product-launch-playbook` | Vol. 38 The Product Launch Playbook: Product Hunt, Hacker News, directories and launch week |
| /playbook:mcp-server | `mcp-server-playbook` | Vol. 39 The Mcp Server Playbook: Build, secure and publish MCP servers for Claude and other agents |
| /playbook:claude-skills-agents | `claude-skills-agents-playbook` | Vol. 40 The Claude Skills & Agents Playbook: Turn your know-how into skills, subagents and automations |
| /playbook:ai-automation | `ai-automation-playbook` | Vol. 41 The Ai Automation Playbook: n8n, Zapier and agents for business operations |
| /playbook:rag-knowledge-base | `rag-knowledge-base-playbook` | Vol. 42 The Rag & Knowledge Base Playbook: Make AI answer from your own documents |
| /playbook:stripe-payments | `stripe-payments-playbook` | Vol. 43 The Stripe & Payments Playbook: Checkout, subscriptions, tax, webhooks and refunds |
| /playbook:saas-metrics-finance | `saas-metrics-finance-playbook` | Vol. 44 The Saas Metrics & Finance Playbook: MRR, CAC, LTV, runway and pricing math |
| /playbook:app-store-launch | `app-store-launch-playbook` | Vol. 45 The App Store Launch Playbook: Submission, review rejections, ASO and ratings |
| /playbook:legal-privacy-playbook-for-small-saas | `legal-privacy-playbook-for-small-saas` | Vol. 46 The Legal & Privacy Playbook For Small Saas: Terms, privacy, GDPR/CCPA, cookies, licences (not legal advice) |
| /playbook:app-security | `app-security-playbook` | Vol. 47 The App Security Playbook: Auth, secrets, OWASP basics and AI-code risks |
| /playbook:customer-interview | `customer-interview-playbook` | Vol. 48 The Customer Interview Playbook: Research that finds what people will pay for |
| /playbook:ai-customer-support | `ai-customer-support-playbook` | Vol. 49 The Ai Customer Support Playbook: Help centre, AI agent replies, escalation |
| /playbook:outsourcing-freelancer | `outsourcing-freelancer-playbook` | Vol. 50 The Outsourcing & Freelancer Playbook: Briefs, hiring, review and paying contractors |
| /playbook:niche-saas-ideas | `niche-saas-ideas-playbook` | Vol. 51 The Niche Saas Ideas Playbook: Find and validate profitable SaaS niches |
| /playbook:youtube-short-video | `youtube-short-video-playbook` | Vol. 52 The Youtube & Short Video Playbook: AI-assisted scripts, editing and growth |
| /playbook:ai-video-ads | `ai-video-ads-playbook` | Vol. 53 The Ai Video Ads Playbook: UGC-style and product videos with AI, labelled honestly |
| /playbook:newsletter | `newsletter-playbook` | Vol. 54 The Newsletter Playbook: Start, grow and monetise a newsletter |
| /playbook:affiliate-partner-program | `affiliate-partner-program-playbook` | Vol. 55 The Affiliate & Partner Program Playbook: Let others sell for you |
| /playbook:game-monetization | `game-monetization-playbook` | Vol. 56 The Game Monetization Playbook: Premium, DLC and free-to-play without being predatory |
| /playbook:steam-wishlist | `steam-wishlist-playbook` | Vol. 57 The Steam Wishlist Playbook: Store page, festivals and marketing before launch |
| /playbook:ai-game-art-pipeline | `ai-game-art-pipeline-playbook` | Vol. 58 The Ai Game Art Pipeline Playbook: Consistent sprites, 3D and UI with AI |
| /playbook:3d-asset-library | `3d-asset-library-playbook` | Vol. 59 The 3D Asset Library Playbook: Build and sell a 3D asset library |
| /playbook:podcast-launch-growth | `podcast-launch-growth-playbook` | Vol. 60 The Podcast Launch & Growth Playbook: Launch, produce and grow a podcast with AI agents, step by step |
| /playbook:app-logo-mark-design | `app-logo-mark-design-playbook` | Vol. 61 The App Logo & Mark Design Playbook: Design a logo that works at 16px and scales to a store listing. |
| /playbook:claude-directory-submission | `claude-directory-submission-playbook` | Vol. 62 The Claude Directory Submission Playbook: Get your MCP server listed in the Claude Directory in 15 minutes |
| /playbook:self-reliance-book-launch | `self-reliance-book-launch-playbook` | Vol. 63 The Self-Reliance Book Launch Playbook: Research, position and launch a color self-reliance book on KDP |
| /playbook:idea-to-launch | `idea-to-launch-playbook` | Vol. 64 The Idea-To-Launch Playbook: Launch a software product and choose its listing channels with an AI agent |
| /playbook:search-console-seo | `search-console-seo-playbook` | Vol. 65 The Search Console Seo Playbook: Mine your own search data for the next page to fix |
| /playbook:conversion-tracking-cart-recovery | `conversion-tracking-cart-recovery-playbook` | Vol. 66 The Conversion Tracking & Cart Recovery Playbook: Cookie-free source tracking, an email step and Stripe cart recovery |
| /playbook:ai-backlink | `ai-backlink` | Vol.  AI Destekli Backlink Playbook:  |
| /playbook:ai-game-dev-launch-2026 | `ai-game-dev-launch-2026` | Vol.  AI Game Development & Launch Playbook 2026:  |
| /playbook:app-screenshot | `app-screenshot` | Vol.  AI-Assisted App Screenshot Playbook:  |
| /playbook:autonomous-mobile-app-dev | `autonomous-mobile-app-dev` | Vol.  Autonomous Mobile App Development & Polish:  |
| /playbook:claude-saas-growth | `claude-saas-growth` | Vol.  Claude SaaS Growth Playbook:  |
| /playbook:deploy-app-vps | `deploy-app-vps` | Vol.  Uygulamayı VPS'e Yayına Alma:  |
| /playbook:management-sim-design | `management-sim-design` | Vol.  The Management Sim Playbook:  |
| /playbook:mobil-ux-urun-kalitesi-2026 | `mobil-ux-urun-kalitesi-2026` | Vol.  2026 Mobil Uygulama, UX ve Ürün Kalitesi:  |
| /playbook:personal-brand-platforms | `personal-brand-platforms` | Vol.  Personal Brand Platform Playbooks:  |
| /playbook:pixel-art-from-3d | `pixel-art-from-3d` | Vol.  3D'den Gerçekçi Pixel Art Sprite Üretimi:  |
| /playbook:saas-free-growth-checklist | `saas-free-growth-checklist` | Vol.  SaaS Free Growth Playbook & Checklist:  |
| /playbook:saas-organic-growth | `saas-organic-growth` | Vol.  SaaS Organic Growth: Google, Bing & AI Search:  |
| /playbook:seo-expert | `seo-expert` | Vol.  SEO Expert (skill):  |
| /playbook:signal-outreach | `signal-outreach` | Vol.  Signal-Based Outreach Playbook:  |
| /playbook:ui-ux-ai | `ui-ux-ai-playbook` | Vol.  UI/UX AI Playbook:  |
| /playbook:yeni-uygulamalar-growth | `yeni-uygulamalar-growth` | Vol.  Yeni Uygulamalar İçin Growth Playbook:  |
