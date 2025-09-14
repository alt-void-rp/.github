```mermaid
graph TD
    A[Alt:V Core<br>(Real-time)] --> B[Resource: Bank]
    B --> C[Resource: Taxi]
    C --> D[Resource: Jobs]

    E[Website / Launcher / Discord Bot] --> F[API Gateway<br>(Nginx/Traefik)]
    F --> G[Bank Service]
    F --> H[Taxi Service]
    F --> I[Donate Service]
    F --> J[Auth Service]

    G --> K[Database<br>(PostgreSQL/Redis)]
    H --> K
    I --> K
    J --> K

    B --> F
    C --> F
    D --> F
