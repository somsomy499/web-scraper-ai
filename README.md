# Web Scraper AI 🕷️

AI-powered web scraping with structure understanding and anti-bot evasion.

## Features

- **Structure Understanding**: LLM-based page parsing
- **Anti-Bot**: Cloudflare, DataDome, PerimeterX bypass
- **Structured Extraction**: JSON output from any page
- **Proxy Rotation**: Built-in proxy management

## Quick Start

```python
from web_scraper_ai import Scraper

scraper = Scraper(proxies=["http://proxy1:8080"])
data = scraper.extract("https://example.com/products", schema=product_schema)
```

## License

MIT