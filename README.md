# CONTINGENT Triptych

A museum-style web installation presenting three [CONTINGENT](https://objkt.com/collections/KT1UAS5N32uiAeQjXjfwkkwh7NUHPQapzLNs) generative artworks side by side.

| Panel | OBJKT | Edition |
|-------|-------|---------|
| Left | [Token 95](https://objkt.com/tokens/KT1UAS5N32uiAeQjXjfwkkwh7NUHPQapzLNs/95) | CONTINGENT #94 |
| Center | [Token 84](https://objkt.com/tokens/KT1UAS5N32uiAeQjXjfwkkwh7NUHPQapzLNs/84) | CONTINGENT #83 |
| Right | [Token 144](https://objkt.com/tokens/KT1UAS5N32uiAeQjXjfwkkwh7NUHPQapzLNs/144) | CONTINGENT #143 |

Each piece loads from IPFS in its own iframe so all three Three.js scenes run concurrently.

## Run locally

```bash
cd contingent-triptych
python3 -m http.server 8080
```

Open http://localhost:8080
