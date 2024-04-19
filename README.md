# device-setup

Files for reusable setup on a new mac device.

## To install apps

You can install multiple apps in one go by placing them all into a text file `apps.txt` and then running brew install:

```bash
xargs -L 1 brew install < apps.txt
```

#### Reference

- https://www.youtube.com/watch?v=GK7zLYAXdDs
- https://github.com/CodingGarden/mac-setup
- https://github.com/CodingGarden/vscode-settings
- https://www.josean.com/posts/7-amazing-cli-tools