# Contributing

Thank you for contributing to repositories under **sirelkhatimgamal**.

## Ground rules

- Production client repositories are private. Do not copy their code into public repos.
- One concern per pull request.
- Module technical names stay stable once a client is live.
- Do not commit `__pycache__`, `.pyc`, `.zip` installers, `.filestore`, or database dumps.
- Do not commit API keys, payment credentials, or `odoo.conf` with passwords.

## Branching

- `main` — production-ready default
- `18.0` / `17.0` — use only when the repo is strictly versioned for Odoo
- Feature branches: `feat/short-name`, fixes: `fix/short-name`

## Pull requests

1. Describe the Odoo version and the module(s) changed
2. List upgrade or data-migration impact
3. Attach screenshots for UI changes (Arabic and English if both exist)
4. Confirm access rights were reviewed

## Code style

- Python: follow Odoo addon conventions (`models`, `views`, `security`, `data`)
- XML IDs must be unique and descriptive
- Prefer inheritance (`_inherit`) over copying core files
