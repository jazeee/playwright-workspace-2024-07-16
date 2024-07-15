# Playwright Workspace

This is a Playwright playground for playwright.dev E2E testing platform.

## Creation

This repo was created using

- `npm init`
- `npm init playwright@latest`
  - Pick `TypeScript` and install defaults

## Usage

- `npm install`

Then to run tests, run one of:

- Run test via CLI: `npm run playwright:test`
- Run tests in UI: `npm run playwright:open`
- Run and debug in VSCode, open a spec file and click the green run test button
- Run and debug in VSCode, open the `Test Explorer` built in extension and run/debug tests.

## Troubleshooting

If your tests don't show up:

- Make sure the file ends in `.spec.ts`
- Make sure `playwright.config.ts` is valid
- In VSCode, open the `Test Explorer` extension and update configurations
  - In command palette: `Test: Toggle Playwright Configs` and adjust as needed.
