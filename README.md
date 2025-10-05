
**Please submit published link here:**
https://yebelo-technology-pvt-ltd-assignmen-tau.vercel.app/

**Please submit screen recording drive link here:**
https://www.loom.com/share/dc56f15d09914cb0b74f07bf28038684?sid=ac91046b-2e02-44aa-91ca-41f364988d8f


**YEBELO Technology Assignment**
**Overview**

Real-time trading analytics system for Solana tokens using Redpanda, Rust, and NextJS.

Streams trade data → calculates RSI → displays live charts.

Tech Stack

Containerization: Docker

Streaming Broker: Redpanda

Backend: Rust

Frontend: NextJS + TypeScript

Charts: Chart.js / Recharts

**Project Structure**
backend/      → Rust API & RSI processor
frontend/     → NextJS dashboard
data/         → trades_data.csv
docker-compose.yml

**Setup**

Start Docker containers: docker compose up -d

Create Redpanda topics: trade-data, rsi-data

Run CSV ingestion script → publish to trade-data

Run Rust backend → calculates RSI → publishes to rsi-data

Start frontend → live charts and current RSI values

**AI Tools Used**

Docker config generation

RSI explanation & calculation

Rust consumer code snippets
