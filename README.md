# rclone-backup

Homepage and privacy policy for a personal, single-user Google OAuth client used with [rclone](https://rclone.org). Google requires both pages before an External OAuth app can be published to production, even if only one person uses it.

The client only ever requests the `drive.file` scope, so it can see just the files it creates. Those files are [restic](https://restic.net) backups, encrypted before upload.

Served by GitHub Pages from the repository root: [vshikhar95.github.io/rclone-backup](https://vshikhar95.github.io/rclone-backup/).
