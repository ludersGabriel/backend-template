## Run Locally

### Requirements
- Node Version Manager (nvm)
- Yarn
- NodeJS
- Docker and Docker Compose

### Presets

Clone the repo
```bash
  git clone https://github.com/ludersGabriel/backend-template.git
```

Go to the project directory
```bash
  cd backend-template/
```

Setting up the right node version
```bash
  nvm use
```

### Setting up

Installing Dependencies
```bash
  yarn
```

Setting up the .env file
```bash
  cp .env.example .env
```

Initializing the docker container for the database
```bash
  yarn dev:init
```

Setting up the test and dev seeds for the database
```bash
  yarn test:setup
```

Running the graphql server at http://localhost:4000/
```bash
  yarn dev &
```

## Running Tests

The backend has unit tests set up with Jest

Going to the backend directory
```bash
  cd backend
```

Setting up the environment and Running the tests
```bash
  yarn test
```
