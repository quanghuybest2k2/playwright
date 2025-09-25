## Install and run

```bash
cp .env.example .env
```

```bash
npm install
```

Runs the end-to-end tests.

```bash
npm test
```

Starts the interactive UI mode.

```bash
npm run ui
```

## Other Command

Runs the tests only on Desktop Chrome.

```bash
npx playwright test --project=chromium
```

Runs the tests in a specific file.

```bash
npx playwright test example
```

Runs the tests in debug mode.

```bash
npx playwright test --debug
```

Auto generate tests with Codegen.

```bash
npx playwright codegen
```
