pnpm add -D typescript ts-node-dev @types/node
pnpm exec tsc --init
{
  "scripts": {
    "dev": "ts-node-dev --respawn --transpile-only src/index.ts",
    "build": "tsc",
    "start": "node dist/index.js"
  }
}# plop-backend-template
