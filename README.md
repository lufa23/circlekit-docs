# circlekit docs

Documentation for [circlekit](https://github.com/vyperlang/circle-titanoboa-sdk), a
Python SDK for x402 payments through Circle Gateway, built with
[Thally](https://docs.thally.io).

- `src/content/` holds the pages (MDX).
- `docs.json` holds the navigation.
- `openapi.yaml` describes the example endpoint used in the quickstart.

The code in these docs was run end to end against circlekit commit `1a05260` on Arc
Testnet, including a funded payment.

## Work on the docs

```bash
npm install
npx --yes @thallylabs/cli@latest check
npm run dev
```

The site was scaffolded with `npx create-thally-docs@latest`. Files listed in
`starter-release.json` belong to the Thally runtime and are updated through Thally's
update workflow, not by hand.
