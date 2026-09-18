# Security policy

## Reporting

If you find a security issue in a **sirelkhatimgamal** or **seralkhatem3210** repository, **do not open a public issue**.

Contact the owner privately through [sirelkhatim.uk](https://sirelkhatim.uk) or GitHub security advisories.

## Scope

Includes:

- Exposed secrets or credentials
- Unsafe Odoo controllers or missing access rules
- Payment or e-invoice integration flaws

## Practice

- Rotate any key that was committed
- Keep production `odoo.conf` and filestore off GitHub
- Review portal controllers for `auth` and record rules before go-live
