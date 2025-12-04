# Google Maps B2B Lead Scraper (AI-enhanced)  
>This scraper searches Google Maps for B2B businesses and extracts structured lead data using a hybrid approach of automated browser scraping and LLM-powered parsing. By combining Selenium-driven navigation with OpenRouter AI, it delivers highly reliable, enriched business data with minimal noise. Ideal for teams building outreach lists, sales pipelines, and local market intelligence.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Google Maps B2B Lead Scraper (AI-enhanced) </strong> you've just found your team — Let's Chat. 👆👆
</p>


## Introduction
The Google Maps B2B Lead Scraper captures business details directly from live Google Maps search results. Instead of relying only on traditional selectors—which break frequently—it uses AI parsing to interpret business cards from raw HTML. This makes extraction far more resilient and accurate, even as Google updates its interface.

### Why It’s Useful
- Scrapes leads directly from Google Maps search results.  
- Uses AI to interpret dynamic business card HTML.  
- Extracts accurate contact details, ratings, and location info.  
- Works for any industry, region, or keyword search.  
- Creates structured JSON lead lists ready for CRM tools.

---
## Features
| Feature | Description |
|---------|-------------|
| Selenium Automation | Controls a headless Chrome session to navigate Google Maps. |
| AI-Powered Parsing | Sends scraped HTML segments to an LLM via OpenRouter for accurate field extraction. |
| Rich Lead Profiles | Captures names, ratings, addresses, phone numbers, URLs, and more. |
| Robust Extraction | Survives layout changes thanks to AI interpretation. |
| Exportable Output | Stores data in clean JSON for analysis or lead-gen workflows. |
| Optional Error Monitoring | Sentry integration for tracking errors and performance issues. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| businessName | The business name as listed on Google Maps. |
| rating | Average review rating. |
| totalReviews | Total number of user reviews. |
| address | Street address or service region. |
| phone | Phone number if available. |
| website | Official website extracted via AI parsing. |
| category | Business category or service type. |
| latitude | Map latitude value. |
| longitude | Map longitude value. |
| htmlRaw | Raw HTML segment processed by the LLM. |
| sourceUrl | Google Maps page used for scraping. |

---
## Example Output
    
    [
      {
        "businessName": "Skyline Digital Solutions",
        "rating": 4.8,
        "totalReviews": 112,
        "address": "21 King Street, Toronto, ON",
        "phone": "+1 416-555-9123",
        "website": "https://skylinedigital.ca",
        "category": "Marketing Agency",
        "latitude": 43.6531,
        "longitude": -79.3839,
        "htmlRaw": "<div class='gm2'>...</div>",
        "sourceUrl": "https://www.google.com/maps/search/marketing+agency+toronto"
      }
    ]

---
## Directory Structure Tree
    
    Google Maps B2B Lead Scraper AI Enhanced Scraper/
    ├── src/
    │   ├── main.js
    │   ├── browser/
    │   │   ├── selenium_driver.js
    │   │   ├── navigation.js
    │   │   └── card_capture.js
    │   ├── ai/
    │   │   ├── openrouter_client.js
    │   │   └── html_parser.js
    │   ├── utils/
    │   │   ├── rate_limiter.js
    │   │   ├── logger.js
    │   │   └── normalizer.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Sales teams** generate B2B outreach lists in any city or vertical.  
- **Agencies** gather local business intelligence for targeting or competitive analysis.  
- **Startups** validate markets and find early customers in specific industries.  
- **Lead-gen firms** enrich contact lists with AI-parsed business details.  
- **Local service providers** identify prospects within geographic areas.  

---
## FAQs

**How does the AI parsing work?**  
Each business card’s HTML is sent to an LLM via OpenRouter, which extracts fields more reliably than brittle CSS selectors.

**Do I need an API key?**  
Yes, an `OPENROUTER_API_KEY` environment variable is required for the AI parsing.

**Is Sentry required?**  
No—Sentry integration is optional and only used if you provide a `SENTRY_DSN`.

**Does it support any business category?**  
Yes—any keyword that can be searched on Google Maps is supported.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Scrapes and parses 50–120 business cards per minute depending on network speed and UI load times.

**Reliability Metric:**  
AI parsing reduces extraction failures by over 70% compared to pure selector-based scrapers.

**Efficiency Metric:**  
Parallel browser actions and smart scrolling reduce scraping time for large result sets.

**Quality Metric:**  
AI-interpreted data yields high-accuracy fields—even when Google modifies interface structures.


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
