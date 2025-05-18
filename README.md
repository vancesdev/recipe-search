# Recipe Search Engine

A comprehensive recipe search engine built with Go and Apache Solr.

## Features

- Search recipes by ingredients, preparation time, and keywords
- Chrome extension for saving recipes from food.com
- Responsive web interface built with Templ and HTMX
- Ingredient-based filtering (include/exclude ingredients)

## Components

- Solr backend for powerful search capabilities
- Go API for querying and managing recipes
- Web scraper for recipe ingestion
- Chrome extension for easy recipe saving

## Setup

### Prerequisites

- Go 1.21+
- Apache Solr 9.x+
- Docker (optional)

### Installation

1. Clone the repository
2. Configure Solr (see `scripts/setup_solr.sh`)
3. Build the services: