# Calculator API (Spring Boot)

## Task & Branch Assignment

| Person | Name-NPM | VectorUtility Branch (`feat/...`) | ArithmeticUtility Branch (`feat/...`) |
| :--- | :--- | :--- | :--- |
| **A** | Muhammad Hariz Albaari-2406428775 | `vector-add` | `arithmetic-exponent` |
| **B** | Julius Albert Wirayuda-2406425792 | `vector-subtract` | `arithmetic-divide` |
| **C** | Ahmad Faiq Fawwaz Abdussalam-2406397706 | `vector-multiply` | `arithmetic-multiply` |
| **D** | Fadhil Daffa Putra Irawan-2406438271 | `vector-dot-product` | `arithmetic-subtract` |
| **E** | Sabina Maritza Moenzil-2206027583 | `vector-norm` | `arithmetic-add` |

---

## Dev Workflow (Gradle)

**1. Setup & Test**
```bash
git clone https://github.com/ProLan-kelompok-12/individual-preparation
./gradlew clean build  # Build project & download dependencies
./gradlew test         # Run unit tests

```

**2. Feature Implementation**

* **Create Branch:** `git checkout -b feat/<branch-name>` (e.g., `feat/vector-add`)
* **Implement:** Kerjakan method di Service & Controller (termasuk unit test).
* **Verify:** Pastikan `./gradlew test` passed sebelum push.
* **Pull Request:** Push branch -> Create PR ke `main`.

---
