# Cache crate dependencies

Cache all folders related to the given folder, including Rust global folders and its `target` folder.

```yaml
- uses: tensor-foundation/actions/cache-crate@v1
  with:
    folder: ./programs/swap
    key: program-swap
```

- Inputs:
  - `folder`: Path to the folder containing the crate (without trailing slash). **Required**.
  - `key`: A unique key prefix for the cache identifying the crate. **Required**.
