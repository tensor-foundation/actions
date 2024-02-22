# Cache IDL generators

Cache the hidden folder that stores IDL generators, such as Shank and Anchor.

```yaml
- uses: tensor-foundation/actions/cache-idl-generators@v1
  with:
    path: ./.crates/
    key: idl-generators
```

- Inputs:
  - `path`: Path(s) to cache. Defaults to `./.crates/`.
  - `key`: A unique key prefix for the cache. Defaults to `idl-generators`.
