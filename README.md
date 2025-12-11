# DungeonEscape

![Unreal Engine](https://img.shields.io/badge/Engine-Unreal%20Engine%205-blue)

DungeonEscape is a personal Unreal Engine 5 project focused on procedural dungeon generation with tactical combat. This repository contains the full project source, ready to be cloned, built, and run.

---

## ⚡ Project Overview

* **Engine:** Unreal Engine 5.x
* **Programming Language:** C++ (with Blueprints where applicable)
* **Assets:** All content tracked with Git LFS
* **Platforms:** Windows (edit if more platforms are supported)
* **Status:** In development

---

## 📦 Repository Structure

```
DungeonEscape/
├─ Content/             # All game assets (.uasset, .umap)
├─ Config/              # Project configuration files
├─ Source/              # C++ source code
├─ .gitignore           # Ignored folders/files
├─ .gitattributes       # LFS tracking for binaries
├─ DungeonEscape.uproject
└─ README.md
```

**Note:** `Binaries/`, `DerivedDataCache/`, `Intermediate/`, and `Saved/` are excluded from Git and regenerated on build.

---

## 💾 Git LFS

This project uses Git LFS for all Unreal assets:

```
*.uasset
*.umap
*.png
*.jpg
*.fbx
*.wav
*.mp4
```

Ensure you have [Git LFS installed](https://git-lfs.github.com/) before cloning:

```bash
git lfs install
git clone https://github.com/dakotusofborg/DungeonEscape.git
```

---

## 🚀 How to Build

1. Clone the repository:

```bash
git clone https://github.com/dakotusofborg/DungeonEscape.git
```

2. Open the project in **Unreal Engine 5**.
3. Let UE generate any missing project files if prompted.
4. Build and run in the editor.

---

## 🛠️ Recommended Workflow

* **Commits:** Small, incremental, descriptive.
* **Branches:** Feature branches for new gameplay mechanics; merge to `main` after testing.
* **LFS:** Always add new assets via `git add` so LFS tracks them.

---

## 📄 Contributing

This is a personal project. Pull requests are welcome if you want to contribute.
Please respect the `.gitignore` and LFS setup to avoid repo bloat.

---

## 📌 License

[Specify your license here, e.g., MIT, proprietary, etc.]

---

## 🔗 Useful Links

* [Unreal Engine Documentation](https://docs.unrealengine.com/)
* [Git LFS Documentation](https://git-lfs.github.com/)
* [DungeonEscape Project Board / Wiki] (optional)
