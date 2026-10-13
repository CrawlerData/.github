## CrawlerData

Google Shopping and Google Search data as clean JSON, through one REST API.

- **Google Shopping:** product search, every seller's price and shipping per product, product details
- **Google Search:** organic results, Images, News, Local and Autocomplete
- Any country and language, desktop and mobile, live or async with webhooks
- 1 credit per request, from $1.00 per 1,000 credits down to $0.30, no subscription

**Start here:** [crawlerdata.com](https://crawlerdata.com) · [Docs](https://app.crawlerdata.com/docs) · [Examples](https://github.com/CrawlerData/crawlerdata-examples) · [Blog](https://crawlerdata.com/blog)

### Examples by use case

**Google Shopping**

- [google-shopping-scraper](https://github.com/CrawlerData/google-shopping-scraper): search Google Shopping and export products to CSV/JSON (Python and Node.js)
- [google-shopping-sellers-scraper](https://github.com/CrawlerData/google-shopping-sellers-scraper): every seller's price, shipping and total for a product
- [google-shopping-price-tracker](https://github.com/CrawlerData/google-shopping-price-tracker): scheduled price history in SQLite with CSV export and a chart
- [competitor-price-monitoring](https://github.com/CrawlerData/competitor-price-monitoring): compare your catalog with Google Shopping sellers and alert on undercuts
- [map-violation-monitor](https://github.com/CrawlerData/map-violation-monitor): flag sellers below MAP with timestamped evidence

**Google Search**

- [google-search-scraper](https://github.com/CrawlerData/google-search-scraper): Google SERP to JSON/CSV with organic results, ads, People Also Ask and AI Overview (Python and Node.js)
- [google-rank-tracker](https://github.com/CrawlerData/google-rank-tracker): daily keyword positions by country and device with a change report
- [google-local-business-leads](https://github.com/CrawlerData/google-local-business-leads): Google Local results to a lead list CSV
- [google-news-scraper](https://github.com/CrawlerData/google-news-scraper): brand and keyword news monitoring to CSV and JSON Feed

**AI assistants**

- [google-search-mcp-server](https://github.com/CrawlerData/google-search-mcp-server): connect Claude Code, Claude Desktop, Cursor or n8n to the hosted CrawlerData MCP server
