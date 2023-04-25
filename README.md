# Public Send instances
This page holds a list of public [Send][send] instances.

- [Instances](#instances)
- [How to use](#how-to-use)
- [Host your own instance](#host-your-own-instance)
- [Submit changes](#submit-changes)

This page does not give any promises or warranties with regard to instance
security and reliability.

## Instances

Instance URL | Size<br>limit | Time<br>limit | Download<br>limit | Links/Notes | Country | Version
--- | ---: | ---: | ---: | --- | ---: | ---
https://send.vis.ee | 2.5 GiB | 3 days | 10 | [maintainer](https://github.com/timvisee), [contact](https://timvisee.com/contact) | Netherlands 🇳🇱 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.vis.ee/__version__)
https://send.zcyph.cc | 10 GiB | 7 days | 100 | [maintainer](https://github.com/zcyph), [contact](mailto:send@zcyph.cc) | Germany 🇩🇪 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.zcyph.cc/__version__)
https://send.ephemeral.land | 8 GiB | 28 days | 1,000 | - | Germany 🇩🇪 |  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.ephemeral.land/__version__)
https://send.mni.li | 8 GiB | 7 days | 25 | [contact](https://cryptpad.fr/form/#/2/form/view/gj2mDNekg5gf+AKPkTqLGY9W2Fa2rjceLFISeeLZa3Y/) | Germany 🇩🇪 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.mni.li/__version__)
https://send.monks.tools | 5 GiB | 7 days | 50 | - | United States 🇺🇸 |  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.monks.tools/__version__)
https://send.boblorange.net | 2.5 GiB | 7 days | 100 | - | Portugal 🇵🇹 |  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.boblorange.net/__version__)
https://send.aurorabilisim.com | 2.5 GiB | 7 days | 100 | [contact](https://www.aurorabilisim.com/iletisim/) | Turkey 🇹🇷 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.aurorabilisim.com/__version__)
https://send.artemislena.eu | 2.5 GiB | 7 days | 100 | [contact](https://artemislena.eu/contact.html) | Germany 🇩🇪 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.artemislena.eu/__version__)
https://send.datahoarder.dev | 1 GiB | 1 day | 5 | [maintainer](https://github.com/whalehub), [contact](mailto:admin@datahoarder.dev) | Luxembourg 🇱🇺 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.datahoarder.dev/__version__)
https://fileupload.ggc-project.de | 2.5 GiB | 7 days | 100 | - | Germany 🇩🇪 |  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://fileupload.ggc-project.de/__version__)
https://drop.chapril.org | 1 GiB | 5 days | 100 | [contact](https://www.chapril.org/contact.html) | Germany 🇩🇪 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://drop.chapril.org/__version__)
https://send.jeugdhulp.be | 50 MiB | 10 days | 25 | [contact](https://www.jeugdhulp.be/contact) | France 🇫🇷 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.jeugdhulp.be/__version__)
https://files.psu.ru | 16 GiB | 7 days | 500 | no password | Russia 🇷🇺 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://files.psu.ru/__version__)
https://send.portailpro.net | 10 GiB | 30 days | 100 | - | France 🇫🇷 |  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.portailpro.net/__version__)
https://transfer.acted.org | 5 GiB | 14 days | 3,000 | - | France 🇫🇷 |  ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://transfer.acted.org/__version__)
https://send.datenpost.app | 30 GiB | 7 days | 3 | [contact](mailto:info@webality.de) | Germany 🇩🇪 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.datenpost.app/__version__)
https://send.angelic.icu | 2.5 GiB | 7 days | 50 | [contact](mailto:me@angelic.icu) | Romania 🇷🇴 | ![version](https://img.shields.io/badge/dynamic/json?label=version&query=version&url=https://send.angelic.icu/__version__)

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
