# MERN App - Client

This directory will contain the React/TypeScript frontend for the MERN application.

## Expected Scripts

When real code is added, the following npm scripts should be available in `package.json`:

- `dev` - Start development server
- `build` - Build production bundle
- `lint` - Run ESLint for code quality
- `typecheck` - Run TypeScript type checking
- `test` - Run unit tests

## Foundation CI Detection

The foundation CI workflow (`.github/workflows/ci.yml`) will automatically detect this as a Node.js project when:

- A `package.json` file exists in this directory, OR
- Files matching `client/**` pattern are present

Once detected, CI will:

1. Install dependencies with `npm ci`
2. Run `npm run lint --if-present`
3. Run `npm run typecheck --if-present`
4. Run `npm run test --if-present`

## Getting Started

(To be added when real code is implemented)
