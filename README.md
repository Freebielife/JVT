# JVault Token Observatory

## О проекте / токене

Native token of JVault.app, a decentralized staking platform for jettons on TON blockchain.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-23):

- <https://tonapi.io/v2/jettons/EQC8FoZMlBcZhZ6Pr9sHGyHzkFv9y2B5X9tN61RvucLRzFZz>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Snapshot section statuses report collection progress; unavailable data is never fabricated.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Configure your GitHub workflow scheduler before launch.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## JVT sources and refresh

Official website: https://jvault.xyz; project channel: https://t.me/JVault.
Section flag: TONecoFlags #167. Hero logo: official website favicon (metadata image source was unavailable during setup).
GitHub Actions fallback schedule: 13 and 43 minutes each hour (UTC); scheduled execution may be delayed. Shared Cloudflare registration has not been verified.
