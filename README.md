# E-Commerce Frontend

React frontend for the e-commerce demo.

## Prerequisites
- Node.js 18+

## Setup
```bash
npm install
npm start
```

## Environment Variables
- `REACT_APP_PRODUCT_URL` (default: `http://localhost:3001`)
- `REACT_APP_ORDER_URL` (default: `http://localhost:3002`)

## Scripts
- `npm start` - dev server
- `npm test` - tests
- `npm run build` - production build

## Development Workflow (Git Flow)
1. Create a feature branch from `develop`: `feature/<name>`
2. Commit changes on the feature branch
3. Open a PR into `develop`
4. Create a release branch from `develop`: `release/<version>`
5. Merge `release/<version>` into `main` and tag the release
6. Merge `main` back into `develop`
7. For urgent fixes, create `hotfix/<version>` from `main`, then merge into `main` and `develop`
