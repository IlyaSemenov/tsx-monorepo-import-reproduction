# Steps to reproduce

```sh
npm i -g pnpm
pnpm i
cd packages/a
pnpm tsx test.ts  # crashes
cd ../b
pnpm tsx index.ts  # works
```
