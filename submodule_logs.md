# Submodule Logs

This log documents all changes made to submodules in the repository.

This also triggers workflows on submodule updates.  
Submodule changes are automatically pulled and committed when the changes in this log are pushed.

---

## Triggering GitHub Actions

Steps to be followed -

```bash
git pull origin main
git add .
git commit -m "your message"
git push
```

This ensures the latest submodule references are committed and workflows are executed accordingly.

---

## August 01, 2025

- **sse**: added as new submodule
- **mqtt-web**: added as new submodule

## August 02, 2025

- **sse**:
  - updated run tutorial
  - updated feature doc
- **mqtt-web**: updated run tutorial
