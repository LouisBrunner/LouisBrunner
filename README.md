# Hi, my name is Louis

In 2008, I started learning programming, for free, from a website made by volunteers. Software Engineering quickly became my hobby and then my job.

Since 2015 (after my studies were wrapping up and I had a bit more time on my hand), I have been contributing to various projects I use, fixing bugs, adding features I need, improving documentation...
I have always wanted to give back to the community (and the world at large) and repay what I received for free all these years ago by making software more Free and Open.

I have more than a decade of experience through which I learned a very versatile and technology agnostic skillset.
I have worked with many different languages and stacks (C, C++, Golang, Python, Rust, TypeScript, Terraform, etc etc),
in various industries (robotics, IoT, web agencies, compilers & development tools, DevOps, consulting and more).

## My work

I currently focusing most of my time on:

- [valgrind-macos](https://github.com/LouisBrunner/valgrind-macos):
  [![Yearly downloads][valgrind-macos-shield]](https://formulae.brew.sh/analytics/install/365d/)
  [Valgrind's official](https://valgrind.org/) macOS port is severely outdated so I started maintaining my own fork for simplicity of development.
  Most of my work focus on resolving breakages linked to new macOS versions but also improving the port as a whole to make Valgrind more useful on macOS.
- [ha-proton-drive](https://github.com/LouisBrunner/ha-proton-drive):
  [![Active Deployments][ha-proton-drive-shield]](https://analytics.home-assistant.io/)
  a [Home Assistant](https://www.home-assistant.io/) integration allowing you to back up your instance to [Proton Drive](https://proton.me/drive).
- [ha-addons](https://github.com/LouisBrunner/ha-addons):
  a collection of addons for [Home Assistant](https://www.home-assistant.io/).
- [esbuild-plugins](https://github.com/LouisBrunner/esbuild-plugins):
  a collection of Go [esbuild](https://esbuild.github.io/) plugins.

While they do not see active development at the moment, I also maintain:

- [dnd-multi-backend](https://github.com/LouisBrunner/dnd-multi-backend):
  [![dnd-multi-backend monthly downloads][dnd-multi-backend-shield]](https://www.npmjs.com/package/dnd-multi-backend)
  / [![react-dnd-preview monthly downloads][react-dnd-preview-shield]](https://www.npmjs.com/package/react-dnd-preview)
  / [![dnd-multi-backend dependents][dnd-multi-backend-dependents-shield]](https://github.com/LouisBrunner/dnd-multi-backend/network/dependents?dependent_type=REPOSITORY)
  This monorepo contains a set of NPM packages dealing with drag-n-drop, especially with [React](https://react.dev/). They are all based on the [React-DnD](https://github.com/react-dnd/react-dnd) framework.
  Used by [Electron](https://github.com/electron/) and [Servarr](https://github.com/Servarr).
- [checks-action](https://github.com/LouisBrunner/checks-action):
  [![GitHub Dependents][checks-action-shield]](https://github.com/LouisBrunner/checks-action/network/dependents?dependent_type=REPOSITORY)
  a GitHub Action used to manipulate the GitHub Checks API directly from your YAML workflow, including adding annotations on files, matching the outcome of the job, etc.
  Used by [NPM](https://github.com/npm) and [Microsoft](https://github.com/microsoft).
- [diff-action](https://github.com/LouisBrunner/diff-action):
  [![GitHub dependents][diff-action-shield]](https://github.com/LouisBrunner/diff-action/network/dependents?dependent_type=REPOSITORY)
  a GitHub Action to make diffs and publish them as GitHub Checks with automatic regression testing.
  Used by [Traefik](https://github.com/traefik/traefik-helm-chart).
- [avahi2dns](https://github.com/LouisBrunner/avahi2dns):
  ![All times downloads][avahi2dns-shield]
  a tiny DNS server which can be used to query local mDNS records through Avahi, useful to bridge musl's lack of mDNS support.
  Part of Alpine [edge repo](https://pkgs.alpinelinux.org/package/edge/testing/x86_64/avahi2dns) and [documentation](https://wiki.alpinelinux.org/wiki/MDNS).
- [gha-matrix-tester](https://github.com/LouisBrunner/gha-matrix-tester):
  [![Website][gha-matrix-tester-shield]](https://louisbrunner.github.io/gha-matrix-tester/)
  a tool to test [GitHub Actions matrix](https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/run-job-variations) configs and see what's included and why.
- [kodi-addons](https://github.com/LouisBrunner/kodi-addons):
  a collection of addons for [Kodi (XMBC)](https://kodi.tv/), currently only contains one for [Dropout.tv](https://www.dropout.tv/).
- [terraform-aws-ses-forwarder](https://github.com/LouisBrunner/terraform-aws-ses-forwarder):
  a Terraform module to forward [SES](https://aws.amazon.com/ses/) emails to another email, support regex-based routing.
- [go-touchbar](https://github.com/LouisBrunner/go-touchbar):
  a macOS Touch Bar library written in Go.
- [mem-viz](https://github.com/LouisBrunner/mem-viz):
  a tool to visualize memory layout, mostly focused on macOS and dyld cache.

## Contributions

Here is some examples of projects I have contributed to in the past (mostly small fixes):

- [three.js](https://github.com/mrdoob/three.js) (JavaScript): contributed a way to import NURBS stored in FBX files and a small improvement to `LineMaterial`
- [gping](https://github.com/orf/gping) (Python): improved resizing behaviour, including fixing crashes
- [pi-hole](https://github.com/arevindh/pi-hole) (Shellscript): fixed a crontab-related crash
- [sinon](https://github.com/sinonjs/sinon) (and its related [fake-timers](https://github.com/sinonjs/fake-timers)) (JavaScript): various small improvements
- [lua-intf](https://github.com/SteveKChiu/lua-intf) (C++): added support for Lua 5.4
- [mockery](https://github.com/vektra/mockery) (Go): improved support for generics
- [go-ykpiv](https://github.com/go-piv/go-ykpiv) (Go): fix compilation for ARM architecture
- [atom's tree-view](https://github.com/atom/tree-view) (CoffeeScript): improved trash bin handling on Linux
- [terraform-provider-auth0](https://github.com/auth0/terraform-provider-auth0) (Go): fixed a crash when passing `null` in Terraform
- [swftools](https://github.com/matthiaskramm/swftools) (C): improved support for some fonts
- [LIEF](https://github.com/lief-project/LIEF) (Python/C++): improved support for Macho binaries
- [gorm SQLite](https://github.com/go-gorm/sqlite) (Go): improve parsing for CHECK/CONSTRAINT/FOREIGN KEY
- [zed GDScript](https://github.com/GDQuest/zed-gdscript) (Toml): added support for gdshaderinc files
- [HA London TFL](https://github.com/morosanmihail/HA-LondonTfL) (Python): improved departures/arrivals for National Rail trains
- [Physis](https://github.com/redstrate/Physis) (Rust): added GEARSET.dat support (+ other small fixes)
- [V lang](https://github.com/vlang/v/) (V): reported issues and added test cases

[valgrind-macos-shield]: https://img.shields.io/badge/dynamic/regex?cacheSeconds=86400&logo=homebrew&color=%23FBB040&url=https%3A%2F%2Fformulae.brew.sh%2Fapi%2Fanalytics%2Finstall%2F365d.json&search=%22formula%22%3A%22louisbrunner%2Fvalgrind%2Fvalgrind%22%2C%22count%22%3A%22(%5B%5E%22%5D%2B)%22&replace=%241%2Fyear&label=Downloads
[ha-proton-drive-shield]: https://img.shields.io/badge/dynamic/json?cacheSeconds=86400&logo=homeassistantcommunitystore&color=%2341BDF5&url=https%3A%2F%2Fanalytics.home-assistant.io%2Fcustom_integrations.json&query=%24.proton_drive.total&label=Active%20Deployments
[dnd-multi-backend-dependents-shield]: https://img.shields.io/badge/dynamic/regex?cacheSeconds=86400&logo=github&label=Dependents&color=%232088FF&url=https%3A%2F%2Fgithub.com%2FLouisBrunner%2Fdnd-multi-backend%2Fnetwork%2Fdependents%3Fdependent_type%3DREPOSITORY&search=dependent_type%3DREPOSITORY.*%3E%5CW*(%5B%5Cd%2C%5D%2B)%5CW*Repositories&replace=%241&flags=ms
[dnd-multi-backend-shield]: https://img.shields.io/npm/dm/dnd-multi-backend?cacheSeconds=86400&logo=npm&logoColor=&color=%23CB3837&label=dnd-multi-backend
[react-dnd-preview-shield]: https://img.shields.io/npm/dm/react-dnd-preview?cacheSeconds=86400&logo=npm&logoColor=&color=%23CB3837&label=react-dnd-preview
[avahi2dns-shield]: https://img.shields.io/github/downloads/LouisBrunner/avahi2dns/total?cacheSeconds=86400&logo=github&color=%23181717&label=Downloads%20(All-time)
[checks-action-shield]: https://img.shields.io/badge/dynamic/regex?cacheSeconds=86400&logo=githubactions&label=Dependents&color=%232088FF&url=https%3A%2F%2Fgithub.com%2FLouisBrunner%2Fchecks-action%2Fnetwork%2Fdependents%3Fdependent_type%3DREPOSITORY&search=dependent_type%3DREPOSITORY.*%3E%5CW*(%5B%5Cd%2C%5D%2B)%5CW*Repositories&replace=%241&flags=ms
[diff-action-shield]: https://img.shields.io/badge/dynamic/regex?cacheSeconds=86400&logo=githubactions&label=Dependents&color=%232088FF&url=https%3A%2F%2Fgithub.com%2FLouisBrunner%2Fdiff-action%2Fnetwork%2Fdependents%3Fdependent_type%3DREPOSITORY&search=dependent_type%3DREPOSITORY.*%3E%5CW*(%5B%5Cd%2C%5D%2B)%5CW*Repositories&replace=%241&flags=ms
[gha-matrix-tester-shield]: https://img.shields.io/website?cacheSeconds=86400&up_message=Up&up_color=%23222222&down_message=Down&down_color=red&logo=githubpages&logoSize=auto&label=Deployment&url=https%3A%2F%2Flouisbrunner.github.io%2Fgha-matrix-tester%2F
