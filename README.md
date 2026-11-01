# Rallly (LazyCat LPK)

Group scheduling polls — find the best meeting time without back-and-forth.

- Upstream: https://github.com/lukevella/rallly
- Image: `lukevella/rallly:4.9.2` (mirror mode, digest-matched)
- License: AGPL-3.0 (full text in `content/licenses/LICENSE`)
- Containers: app + PostgreSQL 18

## Notes
- No pre-seeded account or default password; the first account is registered by the user.
- Database password and session secret are derived from platform stable secrets.
- Not yet verified on a real device.
