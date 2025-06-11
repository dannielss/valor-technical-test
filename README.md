# Valor Technical Test

## Technologies

- Webpack
- Module Federation
- Zephyr
- React

## How to use

Run the following commands in the root directory.

```bash
pnpm run build
```

Both `host` and `remote` are independently deployed apps, you can check the live demo here: [Live demo](https://daniel-de-sousa-26-host-valor-technical-test-dann-833232647-ze.zephyrcloud.app/)

To be able to use this example, build remote app first. Then find it in https://app.zephyr-cloud.io and set link to 'remoteEntry.js' file. Link should be set in variable remoteUrl (/host/src/index.js).
