## ETM PowerSync

**A local home energy management system built on [nymea](https://nymea.io).**
Solar surplus, EV charging, heat pump (SG-Ready), battery and load shedding — decided on the
controller in your home, with no dependency on a remote service.

- 📖 Documentation: [docs.etm-powersync.fr](https://docs.etm-powersync.fr/en/)
- 🌐 Website: [etm-powersync.fr](https://etm-powersync.fr/en/)
- ⬇️ Raspberry Pi image, app and APT repository: [installation guide](https://docs.etm-powersync.fr/en/installation/)
- 🆕 Release notes: [what's new](https://docs.etm-powersync.fr/en/nouveautes/)

### Repositories

| Repository | What it is | License |
|---|---|---|
| [etm-powersync-energy-plugin-etm](https://github.com/ETM-Schurig/etm-powersync-energy-plugin-etm) | The energy engine: rule-based decisions, safety limits, optimizer protocol | GPL-3.0 |
| [etm-powersync-plugins](https://github.com/ETM-Schurig/etm-powersync-plugins) | Device integrations (EV chargers, weather forecast, generic energy things) | GPL-3.0 |
| [etm-powersync-plugins-modbus](https://github.com/ETM-Schurig/etm-powersync-plugins-modbus) | Modbus integrations (energy meters, inverters, SunSpec) | GPL-3.0 |
| [etm-powersync-remoteproxyclient](https://github.com/ETM-Schurig/etm-powersync-remoteproxyclient) | Remote access client library used by the controller | LGPL-3.0 |
| [etm-powersync-docs](https://github.com/ETM-Schurig/etm-powersync-docs) | Source of docs.etm-powersync.fr (fr/de/en) | CC-BY-4.0 |

The engine runs on its own: every repository here builds and works without any proprietary
component. These repositories are read-only mirrors, published once per release.

ETM PowerSync is a fork of nymea components; nymea is a trademark of its respective owners.

---

🇫🇷 **ETM PowerSync** — gestion d'énergie locale pour la maison, construite sur nymea : surplus
solaire, recharge de la voiture, pompe à chaleur, batterie et délestage, décidés sur le contrôleur
chez vous. Documentation en français : [docs.etm-powersync.fr](https://docs.etm-powersync.fr/).

🇩🇪 **ETM PowerSync** — lokales Energiemanagement für das Haus auf Basis von nymea.
Dokumentation auf Deutsch: [docs.etm-powersync.fr/de](https://docs.etm-powersync.fr/de/).
