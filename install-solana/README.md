# Install Solana

Install Solana with optional caching and verify the installed version.

```yaml
- uses: tensor-foundation/actions/install-solana@v3
  with:
    version: stable
    cache: true
```

- Inputs:
  - `version`: The Solana version to install. Defaults to `stable`.
  - `cache`: Whether the built Solana release should be cached. Defaults to `true`.
