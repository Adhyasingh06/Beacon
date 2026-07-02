# Beacon
> AI-powered News Intelligence SaaS Platform

Beacon is an AI-powered SaaS platform that helps organizations monitor, analyze, and understand news in real time. By combining intelligent news aggregation with large language models, Beacon transforms information overload into concise, actionable insights.

---

## Why Beacon?

Thousands of news articles are published every hour, making it difficult for businesses to stay informed about competitors, industries, and emerging trends.

Beacon automatically collects relevant news, analyzes it with AI, detects important developments, and delivers personalized intelligence through an intuitive dashboard.

---

## Key Features

### News Aggregation
- Collect news from multiple trusted sources
- Monitor companies, industries, and keywords
- Real-time article updates

### AI Intelligence
- AI-powered article summaries
- Key insight extraction
- Sentiment analysis
- Trend detection
- Topic classification

### Smart Search
- Full-text search
- Advanced filters
- Company-specific monitoring

### Personalized Dashboard
- Daily news briefing
- Trending topics
- Saved searches
- Bookmarked articles

### Alerts
- Breaking news notifications
- Custom keyword alerts
- Email digest (planned)

### User Management
- Secure authentication
- User profiles
- Role-based access (planned)

---

## Tech Stack

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- React Query

### Backend

- FastAPI
- SQLAlchemy
- Pydantic
- Alembic

### Database

- PostgreSQL
- Redis (planned)

### AI

- OpenAI API
- LangChain (planned)
- Vector Database (planned)

### Infrastructure

- Docker
- GitHub Actions
- Nginx
- AWS (planned)

---

## Repository Structure

```
frontend/
backend/
docs/
design/
infrastructure/
```

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/<your-username>/beacon.git

cd beacon
```

---

### Backend

```bash
cd backend

python -m venv venv
```

Activate the virtual environment.

Install dependencies.

```bash
pip install -r requirements.txt
```

Run the API server.

```bash
uvicorn app.main:app --reload
```

---

### Frontend

```bash
cd frontend

npm install

npm run dev
```

---

## Documentation

Project documentation is available in the `docs` directory.

- Architecture
- Database Schema
- API Design
- Technical Decisions
- Development Roadmap

---

## Project Roadmap

### Phase 1 — Foundation

- Repository setup
- Frontend scaffold
- Backend scaffold
- PostgreSQL schema
- Architecture design

### Phase 2 — Core Platform

- Authentication
- News ingestion pipeline
- Dashboard
- Search
- AI summaries

### Phase 3 — Intelligence

- Trend detection
- Sentiment analysis
- Topic clustering
- Personalized recommendations

### Phase 4 — Enterprise Features

- Team workspaces
- Alert system
- Analytics
- Admin dashboard

### Phase 5 — Production

- Docker
- CI/CD
- Cloud deployment
- Monitoring
- Performance optimization

---

## Architecture

The architecture diagram is available in:

```
docs/architecture.png
```

---

## Current Status

🚧 Beacon is currently under active development.

The project follows an iterative development approach with regular feature releases and documentation updates.

---

## Future Enhancements

- Multi-language news support
- AI-generated executive briefings
- Predictive trend analysis
- Slack and Microsoft Teams integrations
- Mobile application
- Public REST API
- Browser extension

---

## Contributing

Contributions, ideas, and feedback are welcome. Please open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License.
