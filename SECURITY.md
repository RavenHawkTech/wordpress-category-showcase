# Security Policy

## Supported Security Posture

This repository contains public WordPress plugin code and release metadata for RavenHawk Category Showcase.

## Secrets Policy

Do not commit:

- API keys
- WordPress credentials
- `.env` files
- SQL/database exports
- `wp-config.php`
- private keys
- debug logs
- production backups

The `.gitignore` file blocks common accidental secret and backup file patterns, but it is not a substitute for reviewing commits before pushing.

## WordPress Update Security

Custom plugin updates should use GitHub Release assets rather than mutable raw files from `main`.

Recommended update chain:

```text
versioned source
→ release ZIP
→ GitHub Release asset
→ update manifest
→ WordPress Admin update
```

The update manifest should include:

```json
{
  "version": "x.y.z",
  "download_url": "https://github.com/RavenHawkTech/wordpress-category-showcase/releases/download/.../plugin.zip",
  "sha256": "..."
}
```

## Branch Protection Recommendation

Enable protection on `main`:

1. Go to **Settings → Branches**.
2. Add branch protection rule for `main`.
3. Enable **Require a pull request before merging**.
4. Enable **Require approvals**.
5. Enable **Require status checks to pass before merging** once CI exists.
6. Enable **Require conversation resolution before merging**.
7. Enable **Restrict who can push to matching branches**.
8. Enable **Do not allow bypassing the above settings** if available.

## Reporting Issues

Report security issues privately to the repository owner rather than opening public issues containing exploit details or secrets.
