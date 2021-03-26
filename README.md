# Public Send instances
This page holds a list of public [Send][send] instances.

- [Instances](#instances)
- [How to use](#how-to-use)
- [Host your own instance](#host-your-own-instance)
- [Submit changes](#submit-changes)

## Instances

- https://send.vis.ee/ (10GB, 7 days) ([maintainer](https://timvisee.com/contact))

### How to use

To use a specific instance, simply open the application in your webbrowser.

To use a specific instance from the command line with [ffsend][ffsend], provide
the `--host URL` flag while uploading.

```bash
# ffsend upload to custom host
ffsend upload --host https://send.vis.ee/ FILE
```

### Host your own instance

You can host your own [Send][send] instance. Read the
[deployment](https://github.com/timvisee/send#deployment) or [docker](https://github.com/timvisee/send/blob/master/docs/docker.md) documentation for details.

A docker compose example configuration can be found at:
https://github.com/timvisee/send-docker-compose

If you plan to host it publicly, please consider to add it to this list.

### Submit changes

To submit changes to this list, please open a pull request or issue.

[send]: https://github.com/timvisee/send
[ffsend]: https://github.com/timvisee/ffsend
