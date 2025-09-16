## Docker Setup
This project includes a Dockerfile to containerize the Strapi backend locally.

### How to Build and Run
```bash
docker build -t client-onboarding-backend ./docker
docker run -p 1337:1337 client-onboarding-backend