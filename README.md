# Chain Token List

Static source-of-truth for frontend chain and token options.

## Structure

- `chains.json`
- `tokens/<chain-name>.json` (contoh: `ethereum.json`, `solana.json`)

Atur mapping file token per chain lewat field `tokenList` di `chains.json`.

## Publish

Push this folder to GitHub and point Worker `CONFIG_BASE_URL` to raw URL:

`https://raw.githubusercontent.com/<owner>/<repo>/<branch>/chaintokenlist`
