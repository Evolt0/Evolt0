<div align="center">

# Hi, I'm Evolt0

### Go · Android · Developer Tooling

Building Go service utilities, offline Android apps, and better code navigation for the editor.

<p>
  <a href="https://go.dev/"><img src="https://img.shields.io/badge/Go-0D1117?style=for-the-badge&amp;logo=go&amp;logoColor=00ADD8" alt="Go" /></a>
  <a href="https://kotlinlang.org/"><img src="https://img.shields.io/badge/Kotlin-0D1117?style=for-the-badge&amp;logo=kotlin&amp;logoColor=7F52FF" alt="Kotlin" /></a>
  <a href="https://developer.android.com/"><img src="https://img.shields.io/badge/Android-0D1117?style=for-the-badge&amp;logo=android&amp;logoColor=3DDC84" alt="Android" /></a>
</p>

[Repositories](https://github.com/Evolt0?tab=repositories) · [Stars & interests](https://github.com/Evolt0?tab=stars) · [Contributions](https://github.com/Evolt0?tab=overview#year-list-container)

</div>

---

## About me

- **Go & backend utilities** — Configuration, data clients, authentication, and caching components for services.
- **Android & on-device processing** — Kotlin apps with camera integration, local persistence, and offline recognition, without accounts or a backend.
- **Editors & language services** — LSP-powered navigation, symbol search, unsaved-buffer synchronization, and index reuse.

## Tech stack

Technologies used in my public projects, grouped by area—not a proficiency ranking.

| Area | Technologies & components |
| :--- | :--- |
| Backend | **Go** · JWT · Viper · Logrus |
| Data & caching | **Redis** · **MongoDB** · SQLx · go-cache |
| Android | **Kotlin** · Jetpack Compose · Material 3 · CameraX · Room · Coroutines / Flow |
| On-device recognition & native integration | C++ / JNI · HyperLPR3 · MNN · OpenCV |
| Developer tooling | Go · Luau · LSP · gopls · Eclipse JDT LS · JetBrains Kotlin LSP |
| Build & automation | Gradle · CMake · GitHub Actions · Python release scripts |
| Kubernetes integration | client-go · Kubernetes API |

**Currently exploring:** containerization and orchestration with Docker and Kubernetes.

## Selected projects

### [ParkTick](https://github.com/Evolt0/ParkTick) — Offline parking timer

Photograph a vehicle, recognize and confirm its plate on-device, and track parking time from the moment the photo was taken. No account, backend, or always-running background service.

- **Data & time:** Room persistence, duplicate active-plate detection, and timing recovery across process restarts and device reboots.
- **Privacy & recognition:** App-private photos, cleanup when parking ends, and JNI integration with HyperLPR3, MNN, and OpenCV.
- **Status:** Prerelease validation; target-device testing and recognition-quality acceptance remain open.

### [tern-go-navigation](https://github.com/Evolt0/tern-go-navigation) — Go code navigation

Find definitions and references, search project symbols, and preview source before jumping—all inside Tern's native editor.

- **Interaction:** Unsaved buffers, selected-identifier queries, and per-window jump history without forced saves.
- **Implementation:** Go backend + Luau frontend, reusable gopls sessions and persistent indexes, with macOS / Linux release packages.

### [tern-java-navigation](https://github.com/Evolt0/tern-java-navigation) — Java / Kotlin navigation

Bring Java and Kotlin definitions, references, and project-symbol search to Tern, sharing the Go plugin's navigation UI and jump history.

- **Language services:** A Go bridge to Eclipse JDT LS and JetBrains Kotlin LSP, started on demand and reused across queries.
- **Indexing & boundaries:** Incremental buffer synchronization and per-file symbol-cache invalidation; cross-language coverage follows the underlying servers' capabilities.

### [svcutils](https://github.com/Evolt0/svcutils) — Go service utilities

An earlier collection of backend building blocks: Redis, MongoDB, SQLx, and Kubernetes clients, plus configuration, JWT, and caching helpers.

---

<details>
<summary>GitHub stats · Activity & language breakdown</summary>

<p align="center">
  <a href="https://github.com/Evolt0">
    <img width="400" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Evolt0&amp;show_icons=true&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=58A6FF&amp;icon_color=58A6FF&amp;text_color=C9D1D9" alt="Evolt0's GitHub statistics" />
  </a>
  <a href="https://github.com/Evolt0?tab=repositories">
    <img width="334" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Evolt0&amp;langs_count=6&amp;layout=compact&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=58A6FF&amp;text_color=C9D1D9" alt="Most used languages across Evolt0's public repositories" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Evolt0?tab=overview#year-list-container">View full contribution history →</a>
</p>

</details>
