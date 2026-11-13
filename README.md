# OmniRoute AI Gateway — Back4App Container

Deployable OmniRoute Docker container configured for Back4app Containers PaaS and custom domain routing on `bikinkilat.web.id`.

## Quick Start on Back4app Containers
1. Go to [Back4app Containers Dashboard](https://www.back4app.com/containers).
2. Click **Create new App** -> **Containers As a Service**.
3. Connect your GitHub account and select this repository: `adityaarta085/omniroute-container`.
4. Configure Port: **20128**.
5. Set Environment Variables:
   - `PORT`: `20128`
   - `DATA_DIR`: `/app/data`
   - `REQUIRE_API_KEY`: `true`
   - `JWT_SECRET`: `kYn39eH8L9pZ2xR4wM7qB1vC5tF8aD0sE3gH6jK9mN2pQ5rT8vW1yZ4aB7dE0gJ2`
   - `API_KEY_SECRET`: `a8f1b3e94c2d70851e6a9f3b5c7d0e2f4a6b8c0d2e4f6a8b0c2d4e6f8a0b2c4e`
   - `INITIAL_PASSWORD`: `OmniSecure#2026!BikinKilat`
6. Click **Deploy**.
7. In App **Settings** -> **Domain**, bind `omniroute.bikinkilat.web.id`.
