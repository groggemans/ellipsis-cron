<h1>Installation</h1>

**Requirements:** [Ellipsis][ellipsis]

```bash
# With ellipsis installed
$ ellipsis install ellipsis-cron

# Without ellipsis installed
$ curl -Ls ellipsis.sh | PACKAGES='ellipsis-cron' sh
```

The `.ellipsis/bin` folder should be added to your path. If it isn't you will
need to symlink `.ellipsis/bin/ellipsis-cron` to a folder that is in your path.

[ellipsis]:     https://github.com/ellipsis/ellipsis
