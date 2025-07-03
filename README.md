# NewForm

This project relies on two git submodules to provide both backend and frontend functionality:

- **formio** – backend application
- **formiojs** – frontend library

Clone the repository with submodules initialized:

```bash
git clone --recurse-submodules <repo-url>
```

If you already cloned the repository without submodules you can initialize them with:

```bash
git submodule update --init --recursive
```

## Running the backend

Build and start the backend using `yarn`:

```bash
cd formio
yarn
yarn build:portal
yarn start
```

Optionally you can run the backend using Docker Compose:

```bash
cd formio
docker compose up -d
```
