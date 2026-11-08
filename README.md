## deadlynch

SysAdmin from Curitiba, Brazil. Windows and Linux infrastructure — Active Directory, RDS, file servers, networking.
I like the problems nobody else wants to touch, and I script anything I have to do twice.

Outside work I break old hardware on purpose. Right now: getting Zelda running natively on a Phenom II from 2010.

<p>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Vulkan-AC162C?style=flat-square&logo=vulkan&logoColor=white" />
</p>

### Infra stuff

- [**migrate-fileserver**](https://github.com/deadlynch/migrate-fileserver) — moves Windows shares one department at a
  time and keeps the NTFS ACLs, owners and share permissions. Robocopy alone forgets the share part.
- [**windows-deploy-pipeline**](https://github.com/deadlynch/windows-deploy-pipeline) — deploys over SMB with nothing
  but what Windows already has. No agent, no license, SHA256 on every file.
- [**dayzops**](https://github.com/deadlynch/dayzops) — runs a DayZ server on Linux from one YAML file. Apply, update,
  roll back if it breaks. Has tests and CI.
- [**dayz-ce-tool**](https://github.com/deadlynch/dayz-ce-tool) — edit the server's loot economy without opening a
  24,000-line XML.
- [**rocky_desktop**](https://github.com/deadlynch/rocky_desktop) and [**tcp_tuning**](https://github.com/deadlynch/tcp_tuning)
  — my runbooks (in Portuguese): Rocky Linux workstation on AD, and TCP tuning for SMB servers.

### Old hardware stuff

[TotK Recomp](https://github.com/valentderah/totk-pc-recomp) and [Savage Wind Recomp](https://github.com/Revivedx/SavageWindRecomp)
turn Switch Zelda games into native PC code. They need SSE4, and my Phenom II doesn't have it. So I ported them.

- [**totk-pc-recomp-k10**](https://github.com/deadlynch/totk-pc-recomp-k10) — K10 build, a checker that rejects any
  instruction the CPU can't run, builds trained on the machine that plays them, and a Steam Deck profile.
- [**SavageWindRecomp-K10**](https://github.com/deadlynch/SavageWindRecomp-K10) — same port, plus a Linux fix for
  everyone: the Vulkan recorder thread never started.

One fix merged upstream ([#762](https://github.com/valentderah/totk-pc-recomp/pull/762)), one in review
([#995](https://github.com/valentderah/totk-pc-recomp/pull/995)). Made with Claude Code. Every number I post was
measured on real hardware — if I didn't measure it, I don't claim it.

Thanks to valentderah, Revivedx and everyone behind the original projects.
