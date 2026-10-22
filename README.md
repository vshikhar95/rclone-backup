# rclone-backup

Homepage, privacy policy and terms for two personal, single-user Google OAuth clients: one used with [rclone](https://rclone.org), and `finance-fetch`, which downloads statement attachments from the owner's Gmail (read-only). Google requires these pages before an External OAuth app can be published to production, even if only one person uses it.

The rclone client only ever requests the `drive.file` scope, so it can see just the files it creates. Those files are [restic](https://restic.net) backups, encrypted before upload.

Served by GitHub Pages from the repository root: [vshikhar95.github.io/rclone-backup](https://vshikhar95.github.io/rclone-backup/).

The finance-fetch client requests only `gmail.readonly`, and attachments stay on the owner's computer.
