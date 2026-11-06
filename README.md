# Plateforme maxence.lab-cesi.fr

- caddy : reverse proxy HTTPS (Let's Encrypt), seul service exposé (80/443)
- kuma : supervision, https://status.maxence.lab-cesi.fr
- ntfy : notifications, https://notif.maxence.lab-cesi.fr

Les données sont dans ./data (non versionné) et sauvegardées par restic
chaque nuit (backup-plateforme.timer).
