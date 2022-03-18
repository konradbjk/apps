# TrueCharts<br>
**Community App Catalog for TrueNAS SCALE**

[![docs](https://img.shields.io/badge/docs-rtfm-yellow?logo=gitbook&logoColor=white&style=for-the-badge)](https://truecharts.org/)
[![Discord](https://img.shields.io/badge/discord-chat-7289DA.svg?maxAge=60&style=for-the-badge)](https://discord.gg/tVsPTHWTtr)
[![GitHub last commit](https://img.shields.io/github/last-commit/truecharts/apps?color=brightgreen&logoColor=white&style=for-the-badge)](https://github.com/truecharts/apps/commits)

---
TrueCharts is a catalog of highly optimised TrueNAS SCALE Apps. Made for the community, By the community!

Our primary goals are:

- Micro-Service Centered

- Native Kubernetes

- Stability

- Consistency

All our apps are supposed to work together, be easy to setup using the TrueNAS UI and, above all, give the average user more than enough options to tune things to their liking.

<br>

## Getting started using TrueCharts
[![docs](https://img.shields.io/badge/docs-rtfm-yellow?logo=gitbook&logoColor=white&style=for-the-badge)](https://truecharts.org/)

---
Installing TrueCharts within TrueNAS SCALE, is possible using the TrueNAS SCALE Catalog list.

Check TrueCharts [Quick-Start Guides](https://truecharts.org/manual/Quick-Start%20Guides/01-Adding-TrueCharts/) for more infotmation.

### Support

Please check our [FAQ](https://truecharts.org/about/), [manual](https://truecharts.org/manual/SUPPORT/) and [Issue tracker](https://github.com/truecharts/apps/issues) There is a significant chance your issue has been reported before!

Still something not working as expected? [Contact us!](https://truecharts.org/about/contact/) and we'll figure it out together!

### Roadmap

For big changes we do have a roadmap, every spot on the roadmap is synced to a TrueNAS SCALE Release and should be read as "Should be added at or before this release"


<br>

**Restructure of the Project - TrueNAS SCALE "Bluefin" 22.xx ALPHA 1**

_The current project is hitting internal performance issues, for this reason we need to rework the structure and split some parts of the project into seperate repositories._

<br>

**Refactor the Common Chart - TrueNAS SCALE "Bluefin" 22.xx ALPHA 2**

_The shared Common (chart) basis, used by all our Apps, needs some significant code cleanup. Primarily all code needs to follow a standardised format and comply to the same standard_

<br>

**Increased test coverage - TrueNAS SCALE "Bluefin" 22.xx BETA 1**

_With most parts of our project somewhat cleaned up, we need to work on increasing the coverage of our test system. Our unittests should cover all features and we should also take upgrades into account when testing App changes_


<br>

## Development
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=for-the-badge)](https://github.com/pre-commit/pre-commit)
[![renovate](https://img.shields.io/badge/renovate-enabled-brightgreen?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjUgNSAzNzAgMzcwIj48Y2lyY2xlIGN4PSIxODkiIGN5PSIxOTAiIHI9IjE4NCIgZmlsbD0iI2ZlMiIvPjxwYXRoIGZpbGw9IiM4YmIiIGQ9Ik0yNTEgMjU2bC0zOC0zOGExNyAxNyAwIDAxMC0yNGw1Ni01NmMyLTIgMi02IDAtN2wtMjAtMjFhNSA1IDAgMDAtNyAwbC0xMyAxMi05LTggMTMtMTNhMTcgMTcgMCAwMTI0IDBsMjEgMjFjNyA3IDcgMTcgMCAyNGwtNTYgNTdhNSA1IDAgMDAwIDdsMzggMzh6Ii8+PHBhdGggZmlsbD0iI2Q1MSIgZD0iTTMwMCAyODhsLTggOGMtNCA0LTExIDQtMTYgMGwtNDYtNDZjLTUtNS01LTEyIDAtMTZsOC04YzQtNCAxMS00IDE1IDBsNDcgNDdjNCA0IDQgMTEgMCAxNXoiLz48cGF0aCBmaWxsPSIjYjMwIiBkPSJNMjg1IDI1OGw3IDdjNCA0IDQgMTEgMCAxNWwtOCA4Yy00IDQtMTEgNC0xNiAwbC02LTdjNCA1IDExIDUgMTUgMGw4LTdjNC01IDQtMTIgMC0xNnoiLz48cGF0aCBmaWxsPSIjYTMwIiBkPSJNMjkxIDI2NGw4IDhjNCA0IDQgMTEgMCAxNmwtOCA3Yy00IDUtMTEgNS0xNSAwbC05LThjNSA1IDEyIDUgMTYgMGw4LThjNC00IDQtMTEgMC0xNXoiLz48cGF0aCBmaWxsPSIjZTYyIiBkPSJNMjYwIDIzM2wtNC00Yy02LTYtMTctNi0yMyAwLTcgNy03IDE3IDAgMjRsNCA0Yy00LTUtNC0xMSAwLTE2bDgtOGM0LTQgMTEtNCAxNSAweiIvPjxwYXRoIGZpbGw9IiNiNDAiIGQ9Ik0yODQgMzA0Yy00IDAtOC0xLTExLTRsLTQ3LTQ3Yy02LTYtNi0xNiAwLTIybDgtOGM2LTYgMTYtNiAyMiAwbDQ3IDQ2YzYgNyA2IDE3IDAgMjNsLTggOGMtMyAzLTcgNC0xMSA0em0tMzktNzZjLTEgMC0zIDAtNCAybC04IDdjLTIgMy0yIDcgMCA5bDQ3IDQ3YTYgNiAwIDAwOSAwbDctOGMzLTIgMy02IDAtOWwtNDYtNDZjLTItMi0zLTItNS0yeiIvPjxwYXRoIGZpbGw9IiMxY2MiIGQ9Ik0xNTIgMTEzbDE4LTE4IDE4IDE4LTE4IDE4em0xLTM1bDE4LTE4IDE4IDE4LTE4IDE4em0tOTAgODlsMTgtMTggMTggMTgtMTggMTh6bTM1LTM2bDE4LTE4IDE4IDE4LTE4IDE4eiIvPjxwYXRoIGZpbGw9IiMxZGQiIGQ9Ik0xMzQgMTMxbDE4LTE4IDE4IDE4LTE4IDE4em0tMzUgMzZsMTgtMTggMTggMTgtMTggMTh6Ii8+PHBhdGggZmlsbD0iIzJiYiIgZD0iTTExNiAxNDlsMTgtMTggMTggMTgtMTggMTh6bTU0LTU0bDE4LTE4IDE4IDE4LTE4IDE4em0tODkgOTBsMTgtMTggMTggMTgtMTggMTh6bTEzOS04NWwyMyAyM2M0IDQgNCAxMSAwIDE2TDE0MiAyNDBjLTQgNC0xMSA0LTE1IDBsLTI0LTI0Yy00LTQtNC0xMSAwLTE1bDEwMS0xMDFjNS01IDEyLTUgMTYgMHoiLz48cGF0aCBmaWxsPSIjM2VlIiBkPSJNMTM0IDk1bDE4LTE4IDE4IDE4LTE4IDE4em0tNTQgMThsMTgtMTcgMTggMTctMTggMTh6bTU1LTUzbDE4LTE4IDE4IDE4LTE4IDE4em05MyA0OGwtOC04Yy00LTUtMTEtNS0xNiAwTDEwMyAyMDFjLTQgNC00IDExIDAgMTVsOCA4Yy00LTQtNC0xMSAwLTE1bDEwMS0xMDFjNS00IDEyLTQgMTYgMHoiLz48cGF0aCBmaWxsPSIjOWVlIiBkPSJNMjcgMTMxbDE4LTE4IDE4IDE4LTE4IDE4em01NC01M2wxOC0xOCAxOCAxOC0xOCAxOHoiLz48cGF0aCBmaWxsPSIjMGFhIiBkPSJNMjMwIDExMGwxMyAxM2M0IDQgNCAxMSAwIDE2TDE0MiAyNDBjLTQgNC0xMSA0LTE1IDBsLTEzLTEzYzQgNCAxMSA0IDE1IDBsMTAxLTEwMWM1LTUgNS0xMSAwLTE2eiIvPjxwYXRoIGZpbGw9IiMxYWIiIGQ9Ik0xMzQgMjQ4Yy00IDAtOC0yLTExLTVsLTIzLTIzYTE2IDE2IDAgMDEwLTIzTDIwMSA5NmExNiAxNiAwIDAxMjIgMGwyNCAyNGM2IDYgNiAxNiAwIDIyTDE0NiAyNDNjLTMgMy03IDUtMTIgNXptNzgtMTQ3bC00IDItMTAxIDEwMWE2IDYgMCAwMDAgOWwyMyAyM2E2IDYgMCAwMDkgMGwxMDEtMTAxYTYgNiAwIDAwMC05bC0yNC0yMy00LTJ6Ii8+PC9zdmc+)](https://github.com/renovatebot/renovate)
[![GitHub last commit](https://img.shields.io/github/last-commit/truecharts/apps?color=brightgreen&logoColor=white&style=for-the-badge)](https://github.com/truecharts/apps/commits)

---

Our development process is fully distributed and agile, so every chart-maintainer is free to set their own roadmap and development speed and does not have to comply to a centralised roadmap.
This ensures freedom and flexibility for everyone involved and makes sure you, the end user, always has the latest and greatest of every App installed.


### Getting into creating Apps

Creating charts takes some getting used to, as it's based on Helm charts. We highly suggest prior know-how on creation/modifying Helm Charts, before taking on the challenge of creating SCALE Apps.

For more information on creating SCALE Apps and Helm charts, please check out our [development manual](https://truecharts.org/)

### Automation and you

We provide a lot of tools to make it easier to develop charts, templates, automated testing, automated fixes, automated docs. Even automated update is included. We also actively try to collaborate with other k8s community projects on tooling, for the betterment of all!

Those tools do, however, take time to develop and are certainly not bug free. If you find mistakes in our tooling, please feel free to repost issues or submit any fixes you feel appropriate!

<br>


## Contact and Support
[![Discord](https://img.shields.io/badge/discord-chat-7289DA.svg?maxAge=60&style=for-the-badge)](https://discord.gg/tVsPTHWTtr)

---

To contact the TrueCharts project:

- Create an issue on [Github issues](https://github.com/truecharts/apps/issues)

- Open a [Support Ticket](https://truecharts.org/discord)

- Send us an [email](mailto://info@truecharts.org)

- Or [join our Discord server](https://truecharts.org/discord)

<br>

<!-- INSERT-DISCORD-WIDGET -->

<br>


## Featured Projects

A lot of our work is based on the great effort of others. We would love to extend special thanks to these projects we owe a lot to:

| <a href="https://www.truenas.com/truenas-scale/"> <img src="https://user-images.githubusercontent.com/7613738/113836934-a1764e00-978d-11eb-8e19-a087c5c1f99b.png" width="150" height="150" /> </a> | <a href="https://k8s-at-home.com/"> <img src="https://user-images.githubusercontent.com/7613738/113837194-e26e6280-978d-11eb-9632-2e1529946302.png" width="150" height="150" /> </a> | <a href="https://traefik.io/traefik/"> <img src="https://user-images.githubusercontent.com/7613738/113837353-0b8ef300-978e-11eb-873e-14769acfe1f1.png" width="150" height="150" /> </a> | <a href="https://www.authelia.com/"> <img src="https://avatars.githubusercontent.com/u/59122411?s=200&v=4" width="150" height="150" /> </a> |
| :---------------: | :---------------: | :---------------: | :---------------: |
| <a href="https://www.truenas.com/truenas-scale/">TrueNAS SCALE</a> |  <a href="https://k8s-at-home.com/">K8S-At-Home</a> | <a href="https://traefik.io/traefik/">Traefik</a> | <a href="https://www.authelia.com/">Authelia</a> |

<br>


## Contributors ✨

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-70-orange.svg?style=for-the-badge)](#contributors)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

---

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://schouten-lebbing.nl"><img src="https://avatars.githubusercontent.com/u/7613738?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kjeld Schouten-Lebbing</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=Ornias1993" title="Code">💻</a> <a href="#infra-Ornias1993" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/truecharts/apps/commits?author=Ornias1993" title="Documentation">📖</a> <a href="https://github.com/truecharts/apps/pulls?q=is%3Apr+reviewed-by%3AOrnias1993" title="Reviewed Pull Requests">👀</a> <a href="#financial-Ornias1993" title="Financial">💵</a></td>
    <td align="center"><a href="http://sqlitebrowser.org"><img src="https://avatars.githubusercontent.com/u/406299?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Justin Clift</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=justinclift" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/whiskerz007"><img src="https://avatars.githubusercontent.com/u/2713522?v=4?s=100" width="100px;" alt=""/><br /><sub><b>whiskerz007</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=whiskerz007" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/stavros-k"><img src="https://avatars.githubusercontent.com/u/47820033?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Stavros Kois</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=stavros-k" title="Code">💻</a> <a href="https://github.com/truecharts/apps/commits?author=stavros-k" title="Documentation">📖</a> <a href="https://github.com/truecharts/apps/issues?q=author%3Astavros-k" title="Bug reports">🐛</a> <a href="https://github.com/truecharts/apps/pulls?q=is%3Apr+reviewed-by%3Astavros-k" title="Reviewed Pull Requests">👀</a> <a href="#financial-stavros-k" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/allen-4"><img src="https://avatars.githubusercontent.com/u/65494904?v=4?s=100" width="100px;" alt=""/><br /><sub><b>allen-4</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=allen-4" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/tprelog"><img src="https://avatars.githubusercontent.com/u/35702532?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Troy Prelog</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=tprelog" title="Code">💻</a> <a href="https://github.com/truecharts/apps/commits?author=tprelog" title="Documentation">📖</a> <a href="#financial-tprelog" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/djs52"><img src="https://avatars.githubusercontent.com/u/1466018?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dan Sheridan</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=djs52" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.cetic.be/Sebastien-Dupont?lang=en"><img src="https://avatars.githubusercontent.com/u/2684865?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sebastien Dupont</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=banzo" title="Documentation">📖</a> <a href="#financial-banzo" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/angelnu"><img src="https://avatars.githubusercontent.com/u/4406403?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Vegetto</b></sub></a><br /><a href="https://github.com/truecharts/apps/pulls?q=is%3Apr+reviewed-by%3Aangelnu" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://nieuwdorp.me"><img src="https://avatars.githubusercontent.com/u/12896549?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Luuk Nieuwdorp</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=luuknieuwdorp" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/natewalck"><img src="https://avatars.githubusercontent.com/u/867868?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nate Walck</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=natewalck" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/warllo54"><img src="https://avatars.githubusercontent.com/u/20650065?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Lloyd</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=warllo54" title="Code">💻</a> <a href="#financial-warllo54" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/dwithnall"><img src="https://avatars.githubusercontent.com/u/5699800?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dave Withnall</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=dwithnall" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/ksimm1"><img src="https://avatars.githubusercontent.com/u/1334526?v=4?s=100" width="100px;" alt=""/><br /><sub><b>ksimm1</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=ksimm1" title="Documentation">📖</a> <a href="https://github.com/truecharts/apps/issues?q=author%3Aksimm1" title="Bug reports">🐛</a> <a href="#financial-ksimm1" title="Financial">💵</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://aaronjohnson.io"><img src="https://avatars.githubusercontent.com/u/1386238?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Aaron Johnson</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=acjohnson" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/ralphte"><img src="https://avatars.githubusercontent.com/u/2996680?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ralph</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=ralphte" title="Code">💻</a></td>
    <td align="center"><a href="http://www.abc-groep.be"><img src="https://avatars.githubusercontent.com/u/2351765?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Joachim Baten</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=joachimbaten" title="Code">💻</a> <a href="https://github.com/truecharts/apps/issues?q=author%3Ajoachimbaten" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/mxyng"><img src="https://avatars.githubusercontent.com/u/2372640?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Michael Yang</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=mxyng" title="Code">💻</a></td>
    <td align="center"><a href="http://cturtle98.com"><img src="https://avatars.githubusercontent.com/u/24465356?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ciaran Farley</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=cTurtle98" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/Heavybullets8"><img src="https://avatars.githubusercontent.com/u/20793231?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Heavybullets8</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=Heavybullets8" title="Documentation">📖</a> <a href="https://github.com/truecharts/apps/commits?author=Heavybullets8" title="Code">💻</a> <a href="https://github.com/truecharts/apps/issues?q=author%3AHeavybullets8" title="Bug reports">🐛</a> <a href="#video-Heavybullets8" title="Videos">📹</a> <a href="#mentoring-Heavybullets8" title="Mentoring">🧑‍🏫</a> <a href="#financial-Heavybullets8" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/662"><img src="https://avatars.githubusercontent.com/u/13599186?v=4?s=100" width="100px;" alt=""/><br /><sub><b>662</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=662" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/alex171"><img src="https://avatars.githubusercontent.com/u/28484494?v=4?s=100" width="100px;" alt=""/><br /><sub><b>alex171</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=alex171" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.youtube.com/channel/UCOk-gHyjcWZNj3Br4oxwh0A"><img src="https://avatars.githubusercontent.com/u/1322205?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Techno Tim</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=timothystewart6" title="Documentation">📖</a></td>
    <td align="center"><a href="http://mingyaoliu.com"><img src="https://avatars.githubusercontent.com/u/3460335?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mingyao Liu</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=MingyaoLiu" title="Code">💻</a> <a href="https://github.com/truecharts/apps/issues?q=author%3AMingyaoLiu" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/NightShaman"><img src="https://avatars.githubusercontent.com/u/12952292?v=4?s=100" width="100px;" alt=""/><br /><sub><b>NightShaman</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=NightShaman" title="Code">💻</a> <a href="https://github.com/truecharts/apps/commits?author=NightShaman" title="Documentation">📖</a> <a href="https://github.com/truecharts/apps/issues?q=author%3ANightShaman" title="Bug reports">🐛</a> <a href="#financial-NightShaman" title="Financial">💵</a></td>
    <td align="center"><a href="https://espadav8.co.uk"><img src="https://avatars.githubusercontent.com/u/115825?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Andrew Smith</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=EspadaV8" title="Documentation">📖</a></td>
    <td align="center"><a href="http://xilix.com"><img src="https://avatars.githubusercontent.com/u/2821?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Bob Klosinski</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=fluxin" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/sukarn-m"><img src="https://avatars.githubusercontent.com/u/10946339?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sukarn</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=sukarn-m" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/sebsx"><img src="https://avatars.githubusercontent.com/u/735033?v=4?s=100" width="100px;" alt=""/><br /><sub><b>sebs</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=sebsx" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Dyllan2000alfa"><img src="https://avatars.githubusercontent.com/u/29694020?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dyllan Tinoco</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=Dyllan2000alfa" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/StevenMcElligott"><img src="https://avatars.githubusercontent.com/u/89483932?v=4?s=100" width="100px;" alt=""/><br /><sub><b>StevenMcElligott</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=StevenMcElligott" title="Code">💻</a> <a href="#financial-StevenMcElligott" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/brothergomez"><img src="https://avatars.githubusercontent.com/u/38558969?v=4?s=100" width="100px;" alt=""/><br /><sub><b>brothergomez</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=brothergomez" title="Code">💻</a> <a href="https://github.com/truecharts/apps/issues?q=author%3Abrothergomez" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Sagit-chu"><img src="https://avatars.githubusercontent.com/u/36596628?v=4?s=100" width="100px;" alt=""/><br /><sub><b>sagit</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=Sagit-chu" title="Code">💻</a> <a href="https://github.com/truecharts/apps/issues?q=author%3ASagit-chu" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://zhouyou.info"><img src="https://avatars.githubusercontent.com/u/8481484?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nevan Chow</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=zzzhouuu" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/soilheart"><img src="https://avatars.githubusercontent.com/u/9056381?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Daniel Carlsson</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Asoilheart" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/dlouie-swir"><img src="https://avatars.githubusercontent.com/u/81386715?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Devon Louie</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Adlouie-swir" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Alex-Orsholits"><img src="https://avatars.githubusercontent.com/u/56907127?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alex-Orsholits</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3AAlex-Orsholits" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Tails32"><img src="https://avatars.githubusercontent.com/u/2036401?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Tails32</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3ATails32" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Menaxerius"><img src="https://avatars.githubusercontent.com/u/25470894?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Menaxerius</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3AMenaxerius" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/hidefog"><img src="https://avatars.githubusercontent.com/u/13468236?v=4?s=100" width="100px;" alt=""/><br /><sub><b>hidefog</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Ahidefog" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/dalgibbard"><img src="https://avatars.githubusercontent.com/u/1159620?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Darren Gibbard</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Adalgibbard" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/barti04"><img src="https://avatars.githubusercontent.com/u/34000663?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Barti</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Abarti04" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Sunii"><img src="https://avatars.githubusercontent.com/u/4595444?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sunii</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3ASunii" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/trbmchs"><img src="https://avatars.githubusercontent.com/u/7928292?v=4?s=100" width="100px;" alt=""/><br /><sub><b>trbmchs</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Atrbmchs" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/PylotLight"><img src="https://avatars.githubusercontent.com/u/7006124?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Light</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3APylotLight" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Boostflow"><img src="https://avatars.githubusercontent.com/u/18465315?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Boostflow</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3ABoostflow" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Trigardon"><img src="https://avatars.githubusercontent.com/u/98973534?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Trigardon</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3ATrigardon" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/dbb12345"><img src="https://avatars.githubusercontent.com/u/52704517?v=4?s=100" width="100px;" alt=""/><br /><sub><b>dbb12345</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Adbb12345" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/karypid"><img src="https://avatars.githubusercontent.com/u/1221101?v=4?s=100" width="100px;" alt=""/><br /><sub><b>karypid</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Akarypid" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/eingemaischt"><img src="https://avatars.githubusercontent.com/u/151498?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Philipp</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Aeingemaischt" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/j0hnby"><img src="https://avatars.githubusercontent.com/u/18377483?v=4?s=100" width="100px;" alt=""/><br /><sub><b>John</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Aj0hnby" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/john-parton"><img src="https://avatars.githubusercontent.com/u/2071543?v=4?s=100" width="100px;" alt=""/><br /><sub><b>John Parton</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Ajohn-parton" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Amasis"><img src="https://avatars.githubusercontent.com/u/7325217?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Marc</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3AAmasis" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/fdzaebel"><img src="https://avatars.githubusercontent.com/u/46503230?v=4?s=100" width="100px;" alt=""/><br /><sub><b>fdzaebel</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Afdzaebel" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/kloeckwerx"><img src="https://avatars.githubusercontent.com/u/97212383?v=4?s=100" width="100px;" alt=""/><br /><sub><b>kloeckwerx</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Akloeckwerx" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/BirdBare"><img src="https://avatars.githubusercontent.com/u/1051490?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Bradley Bare</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3ABirdBare" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/alexthamm"><img src="https://avatars.githubusercontent.com/u/2556372?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alexander Thamm</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Aalexthamm" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/rexit1982"><img src="https://avatars.githubusercontent.com/u/7585043?v=4?s=100" width="100px;" alt=""/><br /><sub><b>rexit1982</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Arexit1982" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/iaxx"><img src="https://avatars.githubusercontent.com/u/13745514?v=4?s=100" width="100px;" alt=""/><br /><sub><b>iaxx</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3Aiaxx" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://xstar97.github.io"><img src="https://avatars.githubusercontent.com/u/9399967?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Xstar97</b></sub></a><br /><a href="https://github.com/truecharts/apps/issues?q=author%3AXstar97" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Ornias"><img src="https://avatars.githubusercontent.com/u/20852677?v=4?s=100" width="100px;" alt=""/><br /><sub><b>ornias</b></sub></a><br /><a href="#video-ornias" title="Videos">📹</a></td>
    <td align="center"><a href="http://joshasplund.com"><img src="https://avatars.githubusercontent.com/u/3958801?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Josh Asplund</b></sub></a><br /><a href="#financial-joshuata" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/midnight33233"><img src="https://avatars.githubusercontent.com/u/25982892?v=4?s=100" width="100px;" alt=""/><br /><sub><b>midnight33233</b></sub></a><br /><a href="#financial-midnight33233" title="Financial">💵</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/kbftech"><img src="https://avatars.githubusercontent.com/u/77502706?v=4?s=100" width="100px;" alt=""/><br /><sub><b>kbftech</b></sub></a><br /><a href="#financial-kbftech" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/hogenf"><img src="https://avatars.githubusercontent.com/u/11094630?v=4?s=100" width="100px;" alt=""/><br /><sub><b>hogenf</b></sub></a><br /><a href="#financial-hogenf" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/hawkinzzz"><img src="https://avatars.githubusercontent.com/u/24587652?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Hawks</b></sub></a><br /><a href="#financial-hawkinzzz" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/bodly2"><img src="https://avatars.githubusercontent.com/u/21004768?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jim Russell</b></sub></a><br /><a href="#financial-bodly2" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/TheGovnah"><img src="https://avatars.githubusercontent.com/u/1300101?v=4?s=100" width="100px;" alt=""/><br /><sub><b>TheGovnah</b></sub></a><br /><a href="#financial-TheGovnah" title="Financial">💵</a></td>
    <td align="center"><a href="https://github.com/famewolf"><img src="https://avatars.githubusercontent.com/u/4558832?v=4?s=100" width="100px;" alt=""/><br /><sub><b>famewolf</b></sub></a><br /><a href="#financial-famewolf" title="Financial">💵</a> <a href="https://github.com/truecharts/apps/issues?q=author%3Afamewolf" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/konradbjk"><img src="https://avatars.githubusercontent.com/u/31480935?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Konrad Bujak</b></sub></a><br /><a href="https://github.com/truecharts/apps/commits?author=konradbjk" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!



## Licence
[![License](https://img.shields.io/badge/License-BSD%203--Clause-orange.svg?style=for-the-badge)](https://github.com/truecharts/apps/blob/master/docs/LICENSE.BSD3)

---

Truecharts as a whole, is based on a BSD-3-clause  license, this ensures almost everyone can use and modify our charts. However: As a lot of Apps are based on upstream Helm Charts, Licences can vary on a per-App basis. This can easily be seen by the presence of a "LICENSE" file in the App root folder.

Some Apps may also contain parts in other licenses, such as libraries or templates, these files can be recognised by their individual headers.


`SPDX-License-Identifier: BSD-3-Clause`

---
![built-with-resentment](http://forthebadge.com/images/badges/built-with-resentment.svg)       ![contains-technical-debt](http://forthebadge.com/images/badges/contains-technical-debt.svg)
