<img width="1792" height="592" alt="Image" src="https://github.com/Aloncie/aloncie/blob/main/ProfileBanner2.png" />

<div align = center>
  
# Hi, I'm Bogdan (Aloncie) 👋

<div align = left>

**Systems Software Engineer | C++20/23 • Linux • Algorithms**

I specialize in writing deterministic, resource-efficient code and building low-level system utilities. Applying a strong Mathematics and Physics background to system architecture, with a focus on zero-overhead abstractions and strict memory hygiene.


<p align="left">
  <summary><h2><b>My stack📚</b></h2></summary>
  <img src="https://skillicons.dev/icons?i=cpp,linux,cmake,docker,git,qt" alt="C++, Linux, CMake, Docker, Git, Qt" title="My Tech Stack" />
</p>

## 🚀 Featured Project: [Rwal](https://github.com/Aloncie/Rwal)

*A cross‑platform wallpaper manager that automatically downloads fresh wallpapers from Wallhaven based on your configuration and applies them on Linux (GNOME, KDE, Hyprland) or Windows.*

- **Architecture:** Strict interface boundaries (`IWallpaperSetter`, `IFileSystem`) decouple business logic from OS‑specific APIs. A single binary adapts at runtime to the current desktop environment (no recompilation), and optional dependencies like `libgio-2.0` are loaded dynamically via `dlopen` so that non‑GNOME users never pay for unused libraries.
- **Lightweight Core:** Removed the Qt framework and rewrote the stack in standard C++20 (`std::jthread`, `std::unique_ptr`, RAII). The size of the binary data has remained almost unchanged in size, but has removed a huge dependency that prevented full cross-platform support.
- **Interactive TUI:** Custom ncurses‑based interface with a state‑machine Navigator pattern, asynchronous wallpaper refresh, and real‑time keyword editing through the system `$EDITOR`.
- **Testing & CI:** Unit and integration tests written with GoogleTest + GoogleMock. GitHub Actions builds and packages the project into `.deb`, `.rpm`, `.tar.gz` and `.zip`, delivering ready‑to‑use binaries on every release.
- **System Integration:** systemd timers for background rotation, hot‑reload of configuration, and offline fallback to locally cached wallpapers when the network is unavailable.

**Stack:** C++20, CMake, Linux API, Win32 API, D‑Bus, libcurl, ncurses, GSettings, GoogleTest & GoogleMock, Docker.

## 📚 Education
Currently completing secondary education (physics‑math focus) while studying systems programming and algorithms at a university level.

## 🧮 Algorithms & Problem Solving
- **Competitive Programming:** Consistent practice on [Codeforces (Profile)](https://codeforces.com/profile/Aloncie) ~1400-1500 rating level and [LeetCode (Profile)](https://leetcode.com/Aloncie/).
- **Core Stack:** Binary Search (Integer & Real Numbers), Greedy Algorithms, Prefix Sums.
- **Focus:** Debugging complex constraints, $O(N)$ optimizations, and preventing integer overflows in high-load scenarios.

## 🛠 Tools & Knowledge Management
- **Environment:** Arch Linux, Neovim, Zsh.
- **Databases & Infrastructure**: PostgreSQL, MySQL, Docker (containerization for local DB environments), Relational Algebra, Query Optimization.
- **Build & CI/CD:** CMake, Git (Conventional Commits), Docker (Multi-stage builds), GoogleTest & GoogleMock.
- **Knowledge Base:** Maintain a 100+ node Zettelkasten system in Obsidian for systematic retention of complex C++ standards and architectural patterns.

---

📫 **Contact & Connect:**
- [LinkedIn](https://www.linkedin.com/in/aloncie) 
- [Email](mailto:Aloncie@proton.me)
- [Telegram](https://t.me/Aloncie)

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Aloncie&theme=holi) 
