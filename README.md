# Live Terpene Viewer

This project is a **client-side HTML/JavaScript web app** that displays **live terpene data** for **vape** and **concentrate** products from [Cookies Florida](https://cookiesflorida.co). It is designed to be fast, sortable, and educational — great for dispensary teams or curious customers.

## Features

- **Live product fetching** from Cookies Florida API (vapes + concentrates)
- **Auto-parses malformed JSON** from the source API
- **Dynamic sortable table** of terpene data with:
  - Product image preview
  - Product name (clickable, links to the store page)
  - Delivery method (subcategory)
  - Individual terpene values (sortable)
- **Terpene info tooltips**  
  - Hover over the ℹ️ icon in each terpene column to get aroma, effect, and health details
- **Row/column highlight on hover**
- **Responsive design** for mobile and desktop
- **Loading bar** shows progress of data fetch

## Data Sources

- **API Endpoint**:  
  `https://cookiesflorida.co/wp-json/dovetail-api/v1/products`

- **Categories Used**:
  - `vapes`
  - `concentrates`

- **Query Parameters**:
  - `retailer` (e.g. `tampa`)
  - `menutype=medical`
  - `orderby=popular`

## Tech Stack

- Pure **HTML**, **CSS**, and **JavaScript**
- No frameworks, build tools, or dependencies
- Can be opened directly as a `.html` file in a browser

## How to Use

1. Clone or download the repo
2. Open the `index.html` file in any browser
3. Append `?retailer=tampa` (or another city) to the URL:
4. Explore and sort the terpene data

## Terpene Overlay Examples

Clicking the yellow ℹ️ icon in the column header will show detailed descriptions. These include:

- **Alpha Pinene**: memory, asthma, pine aroma
- **Beta Caryophyllene**: anxiety, pain relief, spicy notes
- **Linalool**: sleep, relaxation, lavender scent

And many more.

## Customization Ideas

- Add more categories (edibles, flower)
- Filter by strain name or terpene
- Export to CSV
- Save preferences in `localStorage`

## ⚠Disclaimer

This app scrapes data from a live API endpoint not intended for public use. It's for educational or internal display purposes only.

---

Made with 💙 by [BurlyVik]
