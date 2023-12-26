# install with --prod

## bun

- bun@1.0.20

```bash
cd bun && bun i --production
# error: lockfile had changes, but lockfile is frozen
```

## pnpm

- pnpm@8.12.1

```bash
cd pnpm && pnpm install --prod
```

## npm

- npm@10.2.3

```bash
cd npm && npm install --omit=dev
```

## Yarn

- yarn@1.22.0

```bash
cd yarn && yarn install --prod
```
