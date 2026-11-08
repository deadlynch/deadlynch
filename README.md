<h2 align="center">Hey, I'm deadlynch 👋</h2>
<p align="center"><i>SysAdmin from Curitiba, Brazil — solving the problems nobody else wants to touch.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Vulkan-AC162C?style=flat-square&logo=vulkan&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

By day I keep Windows and Linux infrastructure running: Active Directory, RDS, file servers, networking, and a lot of
automation so the same fire never has to be put out twice. By night I take things apart to see how far they go —
like making a 2023 Switch game run natively on a 2010 Phenom II.

```text
$ whoami
deadlynch — sysadmin, automator, stubborn debugger
$ cat ~/.motto
If it can be scripted, it will be. If it can't run here, let's find out why.
```

### 🛠️ Infrastructure & automation

| | |
|---|---|
| [**dayzops**](https://github.com/deadlynch/dayzops) | Declarative game server manager for Linux: one YAML file, idempotent `apply`, atomic updates with rollback, systemd units. Tested, with CI. |
| [**migrate-fileserver**](https://github.com/deadlynch/migrate-fileserver) | Guided PowerShell CLI that moves Windows shares department by department, keeping NTFS ACLs, ownership and the SMB share permissions robocopy leaves behind. |
| [**windows-deploy-pipeline**](https://github.com/deadlynch/windows-deploy-pipeline) | Agentless deploys over SMB with only native Windows tools (PowerShell, Task Scheduler, WMI), with backups, SHA256 checks and logs. |
| [**dayz-ce-tool**](https://github.com/deadlynch/dayz-ce-tool) | Tune a game server's economy from the terminal instead of hand-editing 24k-line XML files. |
| [**rocky_desktop**](https://github.com/deadlynch/rocky_desktop) · [**tcp_tuning**](https://github.com/deadlynch/tcp_tuning) | Runbooks (PT-BR): an AD-joined Rocky Linux workstation, and TCP/IP tuning for SMB servers. |

### ⚙️ Retro hardware, modern games

Two forks of static recompilation projects (Switch ARM64 → native x86-64 + Vulkan), ported to **AMD K10** CPUs
(Phenom II, Athlon II), which lack SSSE3 and SSE4 and were left out of the originals.

| | |
|---|---|
| [**totk-pc-recomp-k10**](https://github.com/deadlynch/totk-pc-recomp-k10) | An `amdfam10` build tier, an ISA checker over the generated code, builds profile-trained on the target machine, and a Steam Deck profile with a benchmark harness. |
| [**SavageWindRecomp-K10**](https://github.com/deadlynch/SavageWindRecomp-K10) | The same K10 port, plus a Linux fix for every CPU: the Vulkan recorder thread never started because its stack couldn't hold the app's thread-local storage. |

Upstream: [totk-pc-recomp#762](https://github.com/valentderah/totk-pc-recomp/pull/762) (merged) ·
[#995](https://github.com/valentderah/totk-pc-recomp/pull/995) (in review). Built with AI assistance (Claude Code),
tested and measured on real hardware.

---

<p align="center"><sub>📍 Curitiba, Brazil · 🇧🇷 Português / 🇺🇸 English</sub></p>
