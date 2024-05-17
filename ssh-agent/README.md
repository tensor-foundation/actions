# SSH Agent

Setup up a SSH agent with the specified key.

```yaml
- uses: tensor-foundation/actions/ssh-agent@v2
  with:
    key: ${{ input.ssh-secret }}
```

- Inputs:
  - `key`: SSH private key secret. **Required**.
