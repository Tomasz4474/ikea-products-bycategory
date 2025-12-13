# IKEA Products Bycategory Scraper

The IKEA Products Bycategory Scraper collects structured product data from IKEA category pages across multiple countries and languages. It helps teams analyze product catalogs, pricing, filters, and availability in a consistent and scalable way.


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
  If you are looking for <strong>ikea-products-bycategory</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction

This project extracts detailed product information from IKEA category listings using configurable parameters such as pagination, sorting, and locale. It solves the challenge of manually browsing large product catalogs by providing clean, structured data ready for analysis.
It is designed for analysts, developers, and e-commerce teams who need reliable IKEA product data at scale.

### Global IKEA Catalog Access

- Supports category pages across 70+ international markets
- Handles localized languages, currencies, and formats
- Extracts both products and category-level metadata
- Designed for repeatable and structured data collection

## Features

| Feature | Description |
|----------|-------------|
| Category-Based Extraction | Collects all products from a single IKEA category URL. |
| Multi-Country Support | Works across global IKEA markets with locale configuration. |
| Sorting Options | Supports relevance, price, rating, name, and new products. |
| Pagination Control | Adjust page size and page number for bulk extraction. |
| Filter Discovery | Extracts available filters such as color, size, and price. |
| Structured Output | Returns clean, nested data ready for analytics pipelines. |

---

## What Data This Scraper Extracts

| Field Name | Field Description |
|-------------|------------------|
| id | Unique IKEA product identifier. |
| name | Product name as listed in the catalog. |
| typeName | Product type or variant description. |
| price | Current price, currency, and display prefix. |
| images | Array of product image URLs. |
| url | Relative product page URL. |
| colors | Available color variations. |
| sizes | Available size options. |
| availability | Stock and availability metadata. |
| filters | Available filtering options for the category. |
| pagination | Page, per-page, and total result information. |

---

## Example Output

    [
        {
            "id": "40299687",
            "name": "EKTORP",
            "typeName": "3-seat sofa",
            "price": {
                "current": 399,
                "currency": "USD",
                "prefix": "$"
            },
            "url": "/us/en/p/ektorp-3-seat-sofa-40299687/",
            "colors": ["Beige", "Gray"],
            "sizes": ["Standard"],
            "availability": {
                "inStock": true,
                "quantity": 12
            }
        }
    ]

---

## Directory Structure Tree

    IKEA Products Bycategory /
    ├── src/
    │   ├── main.js
    │   ├── services/
    │   │   ├── categoryFetcher.js
    │   │   ├── productParser.js
    │   │   └── filterParser.js
    │   ├── utils/
    │   │   ├── localeMapper.js
    │   │   └── pagination.js
    │   └── config/
    │       └── defaults.json
    ├── data/
    │   ├── sample-input.json
    │   └── sample-output.json
    ├── package.json
    └── README.md

---

## Use Cases

- **E-commerce analysts** use it to monitor IKEA category pricing so they can benchmark competitors accurately.
- **Market researchers** use it to compare product availability across countries to identify regional trends.
- **Data teams** use it to build structured IKEA product datasets for dashboards and reporting.
- **Retail strategists** use it to track new product launches and catalog changes over time.

---

## FAQs

**Does this scraper work for all IKEA countries?**
It supports over 70 IKEA markets and adapts to different languages and currencies through locale configuration.

**Can I control how many products are returned?**
Yes, pagination and per-page settings allow you to limit or expand the number of products retrieved.

**What happens if a category has no products?**
The scraper returns an empty results array while still including pagination and filter metadata.

**Is sorting customizable?**
Multiple sorting options are supported, including relevance, price, rating, name, and newest products.

---

### Performance Benchmarks and Results

**Primary Metric:** Processes up to 100 products per page with consistent response times under typical catalog sizes.

**Reliability Metric:** Stable extraction across repeated runs with a high success rate on valid category URLs.

**Efficiency Metric:** Optimized pagination handling minimizes unnecessary requests while covering full catalogs.

**Quality Metric:** High data completeness with accurate pricing, availability, and filter metadata across locales.


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
    </td>
  </tr>
</table>
