# AdRank

AdRank is a backend-focused advertising auction and ranking platform built with Python and FastAPI.

The platform allows advertisers to create and manage advertising campaigns while providing users with relevant sponsored results based on their search queries.

AdRank implements a simplified advertising auction where campaigns are evaluated based on targeting, eligibility, and ranking criteria to determine which sponsored results should be displayed.

## Key Features

- Advertising campaign management
- Keyword-based targeting
- Campaign eligibility filtering
- Auction-based ad selection
- Relevance scoring and ranking
- Sponsored search results

## Architecture

AdRank follows a modular monolith architecture with business logic separated into dedicated application components.

```text
Client
  │
  ▼
Nginx
  │
  ├── React Frontend
  │
  └── FastAPI Backend
        │
        ├── Campaign Management
        └── Search
              │
              ▼
        Auction & Ranking Engine
              │
              ▼
          PostgreSQL
```

## Tech Stack

**Backend:** Python, FastAPI, SQLAlchemy  
**Database:** PostgreSQL  
**Frontend:** React, TypeScript  
**Infrastructure:** Docker, Nginx  
**Testing:** pytest

## Author

**Ivan Devyatkin**
