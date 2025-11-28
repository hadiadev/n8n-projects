# n8n-projects
i add four project in this repository that you can downloads and customized according you.

1. PRACTICE HUNTER (web crawler)
textPRACTICE HUNTER – UK GP Practice Intelligence Engine (n8n)
An advanced web-crawling + AI-powered workflow that discovers hidden decision-maker contacts (Practice Managers, GPs, ICB/PCN emails, phone numbers) from NHS GP surgery websites.  
Uses Google Gemini to intelligently detect staff/contact pages → scrapes them → extracts 12+ high-value fields (emails, phones, system mentions, pain signals, social links, etc.) → outputs clean rows ready for outreach.  
Perfect for healthcare SaaS sales, appointment booking automation, or NHS lead generation.

How to customize for your needs:
Change the source Google Sheet ID (first node) to your own master list of GP URLs/postcodes.
Update the AI Agent prompt to look for different roles (e.g., “Dental Practice Owner”, “Care Home Manager”) or different fields.
Replace “UK GP” keywords with your target industry (dentists, vets, pharmacies, private clinics, etc.).
Adjust the output Google Sheet columns or connect to your CRM (HubSpot, Salesforce, etc.) instead.


2. facebook post generator.json
Description:
textFacebook Post Generator – AI-Powered Social Content Automation (n8n)
Fully automated workflow that creates ready-to-post Facebook content for GP Triage (or any healthcare/tech brand).  
Generates human-written captions, posts, hashtags + realistic AI images (Gemini 2.0 Flash) → uploads to Google Drive → posts directly to your Facebook Page via Graph API.  
One trigger → multiple polished, on-brand posts in seconds.

How to customize:
Change the “topic” field in the first Set node (e.g., “staff burnout”, “missed appointments”, “EHR integration”).
Replace the Facebook Page ID and credentials with your own page.
Switch platform to Instagram/LinkedIn by changing the final posting node (or duplicate the workflow).
Use your own brand name, website, and tone in the AI prompt.
Point the Google Sheet to your content calendar.


3. website Lead Generation from Google Search and Maps.json
Description:
textLocal Lead Generator – Google Search + Maps Scraper (n8n)
Smart lead generation workflow that takes any search query (e.g., “dentist Manchester”, “veterinary clinic Bristol”) and returns real business websites + contact details scraped from Google Search and Google Maps.  
Deduplicates, filters junk, extracts emails/phones when available, and appends clean rows to Google Sheets. Ideal for local SEO agencies, healthcare sales teams, or any location-based outreach.

How to customize:
Connect to the built-in chat trigger or replace with webhook/schedule.
Change the target Google Sheet.
Modify filters (e.g., only .co.uk domains, exclude nhs.uk, require “@” in results).
Add extra parsing steps for different industries (e.g., extract “opening hours”, “services offered”).


4. landing page to ads agent.json
GitHub Description:
textLanding Page → Ads Agent – Instant Localized Ad Creative Generator (n8n)
Give it any landing page URL + target locations → it scrapes the page with Firecrawl → analyzes brand tone, colors, and offer → generates 3–10 location-specific Facebook/Instagram ad variations (copy + photorealistic images via Gemini) → auto-posts or saves to Sheets/Drive.  
Zero manual creative work. Perfect for performance marketers running geo-targeted campaigns.

How to customize:
Update the first Set node with your own landing page URL and target cities.
Change number of variations and aspect ratio (1:1, 4:5, 9:16, etc.).
Replace the Facebook Graph API node with Meta Ads Manager API if you want to create actual ad campaigns (not just organic posts).
Swap Gemini image generation for Flux, DALL·E 3, or SD3 if preferred.
Add your own reference hero image (via “Analyze an image” branch) to force visual consistency.
