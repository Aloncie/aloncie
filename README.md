<img width="1792" height="592" alt="Image" src="https://github.com/Aloncie/aloncie/blob/main/ProfileBanner2.png" />

<div align = center>
  
# Hi, I'm Bogdan (Aloncie) 👋

<div align = left>

**Systems Software Engineer | C++20/23 • Linux Systems & Infrastructure  • Algorithms**

I specialize in writing deterministic, resource-efficient code, building low-level system utilities, and maintaining self-hosted Linux infrastructure. Applying a strong Mathematics and Physics background to system architecture, with a focus on zero-overhead abstractions, strict memory hygiene, and practical system administration.


<p align="left">
  <summary><h2><b>My stack📚</b></h2></summary>
  <img src="https://skillicons.dev/icons?i=cpp,linux,cmake,docker,git" alt="C++, Linux, CMake, Docker, Git" title="My Tech Stack" />
</p>

## 🚀 Featured Project: [Rwal](https://github.com/Aloncie/Rwal)

*A cross‑platform wallpaper manager that automatically downloads fresh wallpapers from Wallhaven based on your configuration and applies them on Linux (GNOME, KDE, Hyprland) or Windows.*

- **Architecture:** Strict interface boundaries (`IWallpaperSetter`, `IFileSystem`) decouple business logic from OS‑specific APIs. A single binary adapts at runtime to the current desktop environment (no recompilation), and optional dependencies like `libgio-2.0` are loaded dynamically via `dlopen` so that non‑GNOME users never pay for unused libraries.
- **Cross-platform via STL:** Eliminated massive framework dependencies (Qt) to achieve native cross-platform support via standard C++20, drastically reducing deployment overhead without bloating the binary.
- **Interactive TUI:** Custom ncurses‑based interface with a state‑machine Navigator pattern, asynchronous wallpaper refresh, and real‑time keyword editing through the system `$EDITOR`.
- **Testing & CI:** Unit and integration tests written with GoogleTest + GoogleMock. GitHub Actions builds and packages the project into `.deb`, `.rpm`, `.tar.gz` and `.zip`, delivering ready‑to‑use binaries on every release.
- **System Integration:** systemd timers for background rotation, hot‑reload of configuration, and offline fallback to locally cached wallpapers when the network is unavailable.

**Stack:** C++20, CMake, Linux API, Win32 API, D‑Bus, libcurl, ncurses, GSettings, GoogleTest & GoogleMock, Docker.

## **🖥️ Infrastructure Project: Self-Hosted Debian Home Server**

*A 24/7 headless Debian Linux server providing local infrastructure, network-level security, and automated media distribution in a resource-constrained environment.*

📺 [Video walkthrough](https://youtu.be/I3JlJ0OKSJ8) · [Configs & Docker Compose](https://github.com/Aloncie/Server)

- **OS Administration:** Configured a lightweight headless Debian environment: BBR and IP forwarding tuning, Docker Engine, v2rayA/Xray on the host, lid-switch handling for a laptop-as-server, and containers running as a non-root user (PUID/PGID 1000).
- **Container Orchestration:** Runs AdGuard Home (host network for DNS), Jellyfin and qBittorrent as separate Docker Compose stacks with a shared media volume, hardware transcoding through `/dev/dri` and direct play to keep CPU load low, and the qBittorrent WebUI bound to a LAN address only.
- **Network & Service Automation:** Deployed DNS-level filtering via AdGuard Home for tracker/ad blocking across local network devices, configured a local proxy, and set up continuous 24/7 torrent seeding and media delivery.

**Stack:** Debian Linux, Docker, Docker Compose, systemd, Bash, AdGuard Home, Jellyfin, qBittorrent, Networking (DNS, TCP/IP, Port Forwarding).

## 📚 Education
Currently completing secondary education (physics‑math focus) while studying systems programming and algorithms at a university level.

## 🧮 Algorithms & Problem Solving
- **Competitive Programming:** Regular practice on [Codeforces](https://codeforces.com/profile/Aloncie), focusing on algorithmic problems with ~1500 difficulty rating, and [LeetCode](https://leetcode.com/Aloncie/).
- **Data Structures & Algorithms:** Binary Search, Greedy Approaches, Two Pointers / Sliding Window, Prefix Sums.
- **Focus:** Debugging complex constraints, $O(N)$ optimizations, and preventing integer overflows in high-load scenarios.

## 🛠 Tools & Knowledge Management
- **Environment:** Arch Linux, Neovim, Zsh.
- **Databases & Infrastructure**: Debian Linux (Self-Hosted 24/7 Server), PostgreSQL, MySQL, Docker & Docker Compose (Multi-container Orchestration), Relational Algebra, Query Optimization.
- **Build & CI/CD:** CMake, Git (Conventional Commits), Docker (Multi-stage builds), GoogleTest & GoogleMock.
- **Knowledge Base:** Maintain a 100+ node Zettelkasten system in Obsidian for systematic retention of complex C++ standards and architectural patterns.

---

📫 **Contact & Connect:**
- [LinkedIn](https://www.linkedin.com/in/aloncie) 
- [YouTube](https://www.youtube.com/@Aloncie)
- [Email](mailto:Aloncie@proton.me)
- [Telegram](https://t.me/Aloncie)
