# Contributing to Business Elite Theme

## Branch Strategy

We use a three-branch strategy:

```
development → release → main
```

### Branches

| Branch | Purpose |
|--------|---------|
| `main` | Production-ready code, releases are created here |
| `release` | Staging branch for preparing releases |
| `development` | Active development |

### Version Bump Keywords

Include in merge commit message:

| Keyword | Effect |
|---------|--------|
| `MAJOR` | `1.0.0` → `2.0.0` |
| `MINOR` | `1.0.0` → `1.1.0` |
| `PATCH` | `1.0.0` → `1.0.1` |

## Development

```bash
git checkout development && git pull
git checkout -b feature/my-feature
# make changes
git push -u origin feature/my-feature
# Create PR to development
```
