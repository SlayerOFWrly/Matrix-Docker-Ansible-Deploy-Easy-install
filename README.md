#### ⚠️ edit the passwords in vars.yml ⚠️
-Configure Google Captcha V2 Invisible Or Email in Matrix Vars.yml to allow security for registration, without it breaks compilation (safety mechanism for spam sign-up)
- Simplified Configs: Config files are streamlined and easy to deploy after minor edits, utilizing Caddy as the preferred reverse proxy over Traefik.
- Jitsi Integration: Uses Jitsi for audio and screen-sharing (capped at 30fps) as a replacement for the native Element Call, which requires federation. Use /addwidget in Element to add Jitsi voice rooms.
- Zero Federation: Federation is disabled by default to block CSAM content and raids, enhancing security, though this breaks federation-dependent features like Element Call.
- Security: Auth variables have default passwords that you must change. Rate limiting for messaging and registration spam is enabled and adjustable.
- Email Registration Disabled: Email verification is removed by default for simplicity, but can be re-enabled.
- MASH Playbook Integration: This setup integrates with the MASH Playbook
