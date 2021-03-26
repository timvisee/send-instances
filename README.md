# Public Send instances
This page holds a list of public [Send][send] instances.

- [Instances](#instances)
- [How to use](#how-to-use)
- [Host your own instance](#host-your-own-instance)
- [Submit changes](#submit-changes)

This page does not give any promises or warranties with regard to instance
security and reliability.

## Instances

- https://send.vis.ee/ (10GB, 7 days) ([maintainer](https://github.com/timvisee), [contact](https://timvisee.com/contact))
- https://send.datahoarder.dev/ (1GB, 1 day)
- https://send.navennec.net/ (1GB, 1 day)
- https://send.elasticbyte.io/ (1GB, 1 day)
- https://fileupload.ggc-project.de/ (1GB, 1 day)
- https://send.skyhelm.cloud:8443/ (1GB, 1 day)
- http://send.busyhe.cn/ (1GB, 1 day)
- https://send.portailpro.net/ (10GB, 30 days)
- https://bytefile.de/ (5GB, 7 days)
- https://transfer.acted.org/ (5GB, 7 days)

---

## How to use

To use a specific instance, simply open the application in your webbrowser.

To use a specific instance from the command line with [ffsend][ffsend], provide
the `--host URL` flag while uploading.

```bash
# ffsend upload to custom host
ffsend upload --host https://send.vis.ee/ FILE
```

## Host your own instance

You can host your own [Send][send] instance. Read the
[deployment](https://github.com/timvisee/send#deployment) or [docker](https://github.com/timvisee/send/blob/master/docs/docker.md) documentation for details.

A docker compose example configuration can be found at:
https://github.com/timvisee/send-docker-compose

If you plan to host it publicly, please consider to add it to this list.

## Submit changes

To submit changes to this list, please open a pull request or issue.

[send]: https://github.com/timvisee/send
[ffsend]: https://github.com/timvisee/ffsend
