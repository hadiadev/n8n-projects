>>>n8n Projects Repository

This repository contains four fully-automated n8n workflows that you can download, customize, and use for your business, agency, or automation needs.

Each workflow is modular, editable, and powered by AI (Gemini / OpenAI / Firecrawl).

>>>>1. PRACTICE HUNTER (Web Crawler)
UK GP Practice Intelligence Engine (n8n)

An advanced web-crawling + AI-powered intelligence workflow that discovers hidden decision-maker contacts (Practice Managers, GPs, PCN/ICB emails, phone numbers) from NHS GP websites.

What it does:

Uses Gemini AI to detect staff/contact pages automatically

Scrapes website content

Extracts 12+ high-value outreach fields

Generates structured, clean output rows

Ideal for healthcare SaaS, automations, and NHS lead generation

How to Customize:

Replace Google Sheet ID with your own list of URLs/Postcodes

Modify roles in the AI prompt (Dentists, Care Homes, Vets, Private Clinics, etc.)

Change industry keywords

Send results directly into HubSpot / Salesforce / Airtable

Add more fields like “Services Offered”, “Opening Hours”, etc.

>>>>2. Facebook Post Generator (AI Social Content Automation)
Creates Human-Quality Facebook Posts Automatically

Generates ready-to-publish Facebook content using AI: captions, posts, hashtags, and realistic images.
Uploads visuals to Drive and publishes automatically via Facebook Graph API.

What it does:

AI-generated captions + hashtags + image prompts

Image creation using Gemini 2.0 Flash

Uploads media to Google Drive

Posts automatically to your Facebook Page

One workflow → multiple branded posts instantly

How to Customize:

Edit “topic” in the first Set node (burnout, triage, EHR, etc.)

Replace Facebook Page ID + access token

Change posting destination to Instagram, LinkedIn, Twitter

Add your brand voice, tone, URL

Connect to Google Sheet content calendar

>>>>3. Website Lead Generation (Google Search + Maps Scraper)
Local Lead Generator using Google Search & Google Maps

Takes any search query (e.g., “dentist London”, “vets Birmingham”) and returns real business websites + contact data.

What it does:

Scrapes results from Google Search

Scrapes business info from Google Maps

Extracts websites, phones, emails

Removes duplicates

Sends clean rows to Google Sheets

Ideal for:

Local SEO agencies

Healthcare B2B outreach

Local business lead generation

Geo-targeted outbound campaigns

How to Customize:

Change trigger to webhook, schedule, or manual

Update Google Sheet target

Add filtering rules (only .co.uk, exclude junk links, require emails)

Add extraction for additional fields (services, opening hours, reviews)

>>>>4. Landing Page → Ads Agent
Instant Localized Ad Creative Generator

You provide a landing page URL + target cities → the workflow generates complete localized ad packages (copy + images).

What it does:

Scrapes landing page with Firecrawl

Analyzes brand tone, colors, messaging

Creates multiple geo-targeted ad variations

Generates photorealistic images via Gemini

Saves to Sheets/Drive or posts automatically

Zero manual ad creation needed

How to Customize:

Update landing page URL + list of locations

Increase/decrease number of ad variations

Change image aspect ratio (1:1, 4:5, 9:16)

Swap Gemini image generation with Flux, DALL·E 3, or SD3

Replace Graph API with Meta Ads Manager API for full ads publishing

Add a reference hero image for consistent branding
