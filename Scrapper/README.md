# CryptoViz Scrapper

Web scraping service for collecting cryptocurrency news and data feeds. Built using Selenium.

## Getting Started

### Run

1. Install Docker
2. Clone this repository
3. Build the container: `docker-compose build --no-cache && docker-compose up -d`
4. Run the container: `docker-compose up -d`

### Develop

1. [Install scrappy](https://docs.scrapy.org/en/latest/intro/install.html)
2. [Try this tutorial](https://shinesolutions.com/2018/09/13/running-a-web-crawler-in-a-docker-container/)

## Dependencies

- Scrapy
- Selenium for dynamic scraping

## Features

- Real-time scraping from multiple sources
- Producer for Confluent/Kafka queue

## Deployment

The scraper is containerized using Docker. For Kubernetes deployment, refer to the `_Infra` repository.
