# Terrabit Connect PostgreSQL — releases

Signed Windows releases of **Terrabit Connect PostgreSQL** (`tc-postgresql`), the Terrabit agent that runs named, read-only PostgreSQL queries for Odoo.

The agent's updater reads `latest.json` from the latest release here and installs a new version only if its zip carries a valid **minisign** signature from the key compiled into the agent:

```
untrusted comment: minisign public key A27B3801853BDF29
RWQp3zuFATh7onKK1/jzCnSiAoPlsOUqwdglm4zMnGLltU23HkzchK7J
```

Manual check: `minisign -Vm tc-postgresql-<version>-windows-x64.zip -P RWQp3zuFATh7onKK1/jzCnSiAoPlsOUqwdglm4zMnGLltU23HkzchK7J`

© Terrabit Solutions SRL
