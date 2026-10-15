# Security

- Never commit `.env`.
- `SECRET_KEY` must come from the environment. There is no default in code.
- CORS is an allowlist. Do not set `CORS_ORIGINS=*`.
- Tokens are JWTs. Treat them as credentials.
