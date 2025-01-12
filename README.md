# Flux Chat


## Getting Started

Follow these steps to clone the repository, set it up with Docker Compose, and start the application.

### Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Korbut-Dima/flux-chat-builder.git
   ```

2. Start the application using Docker Compose:

   ```bash
   docker-compose up --build -d
   ```

3. Once the containers are up and running, open your browser and go to:

   ```
   http://localhost
   ```

### Test User Credentials

Use the following credentials to log in as a test user:

- **Email:** `test1@example.com`
- **Password:** `password`

### Stopping the Application

To stop the application and remove the containers, run:

```bash
docker-compose down
```

### Troubleshooting

If you encounter any issues, try the following:

1. Ensure Docker and Docker Compose are installed and running.
2. Rebuild the containers:

   ```bash
   docker-compose up --build
   ```

3. Check the logs for any errors:

   ```bash
   docker-compose logs
   ```


