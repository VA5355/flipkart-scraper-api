# Flipkart Scraper API

API to scrape search results and product details from Flipkart

**Disclaimer:** I am not affiliated or linked to flipkart in any way. This repository is an exploratory project and not meant for commercial use.

---

![Flipkart API Banner](/banner.png)

![Version](https://img.shields.io/badge/dynamic/toml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fva5355%2Fflipkart-scraper-api%2Fmain%2FCargo.toml&query=package.version&label=version)
[![GitHub license](https://img.shields.io/github/license/va5355/flipkart-scraper-api)](https://github.com/va5355/flipkart-scraper-api/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/va5355/flipkart-scraper-api)](https://github.com/va5355/flipkart-scraper-api/issues)
[![Telegram](https://img.shields.io/badge/-va5355-blue?style=flat&logo=telegram)](https://t.me/va5355)
[![Documentation](https://img.shields.io/badge/API-Documentation-blue)](https://scraper-api-eyiz.onrender.com/)

**For documentation visit :** [Flipkart Scraper API](https://scraper-api-eyiz.onrender.com/)

---

## Notice

This API is being shipped only as a Docker image now and not as a hosted URL, due to over-exploitation of the API and lack of funds & free-tier limitations. The hosted API URL has been taken down. [Check out Deployement using Docker](#deployment)

The API has been rewritten in Rust. With this process, a multitude of unexpected errors have been addressed with improved accuracy and better scraping mechanism. [Refer issue #13](https://github.com/va5355/flipkart-scraper-api/issues/13) and [Refer issue #12](https://github.com/va5355/flipkart-scraper-api/issues/12).

---

## Deployment

Supported Deployments

![Cargo](https://img.shields.io/badge/Cargo--red?logo=rust) ![Docker](https://img.shields.io/badge/Docker--blue?logo=docker) ![Nix](https://img.shields.io/badge/Nix--blue?logo=nixos)

[For information on Deployment, refer documentation.](https://scraper-api-eyiz.onrender.com/#deployment)

---

## Features

- API **does not require any client id/secret or any other authorisation** unlike most of Flipkart API
- Completely Open Source
- Fetch search results from [Flipkart](https://www.flipkart.com/)

    Response in JSON format including the following information :
  - Product Name
  - Product Current Price
  - Product Original Price
  - Discount status (`true` or `false`)
  - Product Thumbnail

- Fetch product result from URL of product

    Response in JSON format including the following information about Product :
  - Product Full Name
  - Current and Original Price
  - Discount status and Discount percentage
  - User Rating
  - Stock avalibility (`true` or `false`)
  - Flipkart Assured Product (`true` or `false`)
  - Share URL (More presentable URL)
  - Seller Information (Seller Name and Rating)
  - Product Thumbnails
  - Highlights
  - Available Offers / Bank Offers
  - Specifications

- The API also removes all trackers & loggers in every link from flipkart giving an completely unbaised and cleaner output.

---

## License & Copyright

- This Project is [Apache-2.0](./LICENSE) Licensed
- Copyright 2025 [Sales Man](https://github.com/VA5355)

---
