# AffiliatePulse

**An all-in-one affiliate marketing dashboard** to manage, track, and optimize your affiliate marketing funnels and track performance across multiple revenue streams.

Built by Mark Hardy — Splitwindowbus E-Commerce LLC

---

## Data Entities

### AffiliateLink
Tracks all affiliate products and their performance.
- title: Product/offer name
- description: Short description
- original_url: Base product URL
- affiliate_username: Your affiliate username
- full_affiliate_url: Full tracking URL with affiliate tag
- niche: Market niche
- clicks: Total click count
- earnings: Total earnings ($)
- is_active: Active status

### Contact
Your leads and subscriber database.
- first_name, last_name, email, phone
- source: Where they came from
- tags, status, notes

### EmailBlast
Email campaigns sent to contacts.
- subject, body
- affiliate_link_id: Linked affiliate offer
- status: Draft/Sent/Scheduled
- sent_count, sent_date

### LandingPage
Landing pages for each affiliate offer.
- title, headline, subheadline, body_text
- cta_button_text, affiliate_link_id
- image_url, video_url, slug
- views, is_published

### ShareReminder
Scheduled reminders to post on social media.
- title, affiliate_link_id
- platform: TikTok, IG, etc.
- scheduled_time, repeat, notes, completed

---

## Current Affiliate Links

- Ethereal Commerce: https://magnificent-pure-ethereal-shop.base44.app?aff=doi8utyaf (Money making software)

---

## Key Features
- Dashboard to track clicks and earnings across all affiliate links
- Contact/lead management database
- Email blast campaigns tied to affiliate offers
- Landing page builder for each offer
- Social media share reminders
- Multi-stream revenue tracking

---

Built on Base44 | Owner: hrdymrk | Splitwindowbus E-Commerce LLC
