# Project setup
1. Install dependencies
npm install
2. Create .env file in the project root:
APP_URL=https://fe-delivery.tallinn-learning.ee
3. For CI
Add APP_URL as a secret in GitHub
Settings → Secrets and variables → Actions → New repository secret

## Run tests
Run all tests locally -> npx playwright test
Show test report -> npx playwright show-report
