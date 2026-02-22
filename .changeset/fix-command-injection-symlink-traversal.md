---
'vercel': patch
---

fix(security): replace shell-interpolated execSync with spawnSync argument arrays in mcp command to prevent command injection; validate symlink targets in unzip to prevent path traversal
