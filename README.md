# Heroku aria2c

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Optionally sync downloaded file to your cloud drive with Rclone

1. Setup Rclone by following offical instructions: https://rclone.org/docs/
2. Find the drive you want to use, and copy its `type = ...` to  `... token = ...` section.
3. Replace all linebreaks with `\n`
4. Deploy with the button above, and paste that text in `RCLONE_CONFIG`
5. Set `RCLONE_DESTINATION` to a path you want to store your downloaded files.

