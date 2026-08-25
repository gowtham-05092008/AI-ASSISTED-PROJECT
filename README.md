# AI-Assisted Smart Logistics and Delivery Management Platform

A six-phase full-stack logistics platform built with Python, FastAPI, MySQL, HTML/CSS/JavaScript, analytics, route optimization, QR codes, and AI-ready services.

## Quick start

1. Install Python 3.11+ and MySQL 8+.
2. Create a database named `smart_logistics`.
3. Copy `.env.example` to `.env` and update credentials.
4. Install dependencies:
   `pip install -r requirements.txt`
5. Run the SQL files in `database/`:
   - `schema.sql`
   - `seed.sql`
6. Start the API:
   `uvicorn backend.app.main:app --reload`
7. Open `frontend/index.html` or serve the frontend with a local HTTP server.

API documentation:
`http://127.0.0.1:8000/docs`

## Project phases

- Phase 1: Core shipment, order, warehouse, inventory, fleet and delivery management
- Phase 2: Analytics and performance monitoring
- Phase 3: Route optimization and decision support
- Phase 4: Full-stack customer/admin/driver portal
- Phase 5: Maps, QR, notifications and external service integration
- Phase 6: Testing, Docker, CI/CD and governance

## Demo accounts

After running seed.sql:
- Admin: admin@logistics.local / admin123
- Customer: customer@logistics.local / customer123
- Driver: driver@logistics.local / driver123

Change these passwords before production use.
