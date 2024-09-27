![](https://img.shields.io/badge/Built%20with%20%E2%9D%A4%EF%B8%8F-at%20Technologiestiftung%20Berlin-blue)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

# Kiezbox 2.0

The "Kiezbox 2.0" is a pilot project under the "Gemeinsam Digital: Berlin" strategy, aiming to prototype an alternative, self-sufficient communication network for crisis situations. The _Kiezbox Core_ module differntiates in two modes:
- In **emergency mode**, when electricity fails, _the Kiezbox Core_ creates an independent emergency Wi-Fi network using multiple Kiezbox Cores in a mesh network that allows citizens to communicate with critical infrastructure operators, such as sending text-based emergency messages to a nearby fire department.
- In **normal mode**, the _Kiezbox Core_ uses an additional _sensor module_ to collect environmental data such as temeprature, humidity and noise and transmits this microclimate Kiez-based data via it's own LoRaWAN mesh to a web-based info portal, where informations are accessible to the public.


<img width="1000" alt="Kiezbox_Core_TSB" style="align:center" src="https://github.com/user-attachments/assets/e85f490a-3828-4634-a160-9f082cdefddf">


In addtion to the hardware, two applications will be developed.  This dual functionality ensures both crisis resilience and ongoing data collection for urban planning and public use.

## Related Repositories
This project is composed of multiple repositories:
- [Meshtastic Firmware](https://github.com/technologiestiftung/kiezbox-meshtastic-firmware)
- [Meshtastic Python](https://github.com/technologiestiftung/kiezbox-meshtastic-python)
- [Meshtastic Protobuf Definitions](https://github.com/technologiestiftung/kiezbox-meshtastic-protobufs)
- [OpenWRT Config](https://github.com/technologiestiftung/kiezbox2-openwrt-env)
- [OpenWRT Feed](https://github.com/technologiestiftung/kiezbox2-openwrt-feed)
- [OpenWRT Files](https://github.com/technologiestiftung/kiezbox2-openwrt-files)
- [Kiezbox Monitoring Sensors](https://github.com/technologiestiftung/Kiezbox-Sensors-)
- Emergency Messenger Frontend (coming soon)
- Normal Mode Infor Portal Frontend (coming soon)


## Documentation

You can find the documentation in this repos [Wiki](https://github.com/technologiestiftung/kiezbox/wiki)

## Add contributors
Do you want to honor all kinds of contributions? Use [all-contributors](https://allcontributors.org/)

```bash
npx all-contributors-cli check
npx all-contributors-cli add ff6347 doc
```
You can use it on GitHub just by commenting on PRs and issues:

```plain
@all-contributors please add @ff6347 for infrastructure, tests and code
```

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/JTaIoT"><img src="https://avatars.githubusercontent.com/u/114985716?v=4?s=64" width="64px;" alt="JTaIoT"/><br /><sub><b>JTaIoT</b></sub></a><br /><a href="#infra-JTaIoT" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/technologiestiftung/kiezbox/commits?author=JTaIoT" title="Code">💻</a> <a href="https://github.com/technologiestiftung/kiezbox/commits?author=JTaIoT" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/james-knippes"><img src="https://avatars.githubusercontent.com/u/30473830?v=4?s=64" width="64px;" alt="helican"/><br /><sub><b>helican</b></sub></a><br /><a href="#infra-james-knippes" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/technologiestiftung/kiezbox/commits?author=james-knippes" title="Code">💻</a> <a href="https://github.com/technologiestiftung/kiezbox/commits?author=james-knippes" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## Content Licensing

Texts and content available as [CC BY](https://creativecommons.org/licenses/by/3.0/de/).

## Credits

<table>
  <tr>
    <td>
      Made by  <a href="https://www.technologiestiftung-berlin.de/">
        <br />
        <br />
        <img width="150" src="https://logos.citylab-berlin.org/logo-technologiestiftung-berlin-de.svg" />
      </a>
    </td>
    <td>
      A project by <a href="https://citylab-berlin.org/de/start/">
        <br />
        <br />
        <img width="200" src="https://logos.citylab-berlin.org/logo-citylab-berlin.svg" />
      </a>
    </td>
    <td>
      Supported by <a href="https://www.berlin.de/rbmskzl/">
        <br />
        <br />
        <img width="80" src="https://logos.citylab-berlin.org/logo-berlin-senatskanzelei-de.svg" />
      </a>
    </td>
  </tr>
</table>
