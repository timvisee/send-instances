# Public Send instances
This page holds a list of public [Send][send] instances.

- [Instances](#instances)
- [How to use](#how-to-use)
- [Host your own instance](#host-your-own-instance)
- [Submit changes](#submit-changes)

This page does not give any promises or warranties with regard to instance
security and reliability.

## Instances

- https://send.vis.ee (10GB, 7 days) ([maintainer](https://github.com/timvisee), [contact](https://timvisee.com/contact))
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.vis.ee/__version__)
- https://send.silkky.cloud (20GB, 7 days) ([maintainer](https://github.com/silkkycloud), [contact](https://www.silkky.cloud/contact), [privacy policy](https://www.silkky.cloud/privacy))
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.silkky.cloud/__version__) ![uptime](https://img.shields.io/uptimerobot/status/m788305741-3c46d730432b911283507995)
- https://send.niagan.org (8GB, 14 days) ([maintainer](https://github.com/atilleh))
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.niagan.org/__version__)
- https://send.datahoarder.dev (1GB, 1 day) ([maintainer](https://github.com/whalehub), [contact](mailto:admin@datahoarder.dev))
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.datahoarder.dev/__version__)
- https://send.navennec.net (1GB, 1 day)
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.navennec.net/__version__)
- https://fileupload.ggc-project.de (2.5GB, 7 days)
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://fileupload.ggc-project.de/__version__)
- https://drop.chapril.org (1GB, 5 days) ([contact](https://www.chapril.org/contact.html))
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://drop.chapril.org/__version__)
- https://send.portailpro.net (10GB, 30 days)
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.portailpro.net/__version__)
- https://bytefile.de (5GB, 7 days)
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://bytefile.de/__version__)
- https://transfer.acted.org (5GB, 7 days)
  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://transfer.acted.org/__version__)

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
