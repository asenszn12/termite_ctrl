# 🐜 Termite Control (`termite_ctrl`)

**Termite**: Your local terminal-based version control system.  

---

## 🌱 Inspiration
The name **Termite** comes from combining **Terminal** and **Commit**.  
But instead of stopping at *termit*, I went with **termite**.  

Another fun twist is that all commands use `mite-` (e.g., `mite-init`, `mite-add`), which sounds like *might*.  
Think of the vibe:  
> "Feeling cute, **mite-rm** later."  

---

## ⚙️ Tech Stack
- **Python** → Handles scripts and automation for the local version control system.  

---

## 🎥 Live Demo
🚧 **COMING SOON** (Made with Screencastify)  

---

## 📖 Commands

### `mite-init`
Creates a new `.mite` repository in the current directory.  

### `mite-add <filenames...>`
Stages files into the index for the next commit.  

### `mite-commit -m "message"`
Saves staged files into the repository with a commit message.  

### `mite-log`
Shows the history of commits (commit number + message).  

### `mite-show [commit]:<filename>`
Displays the contents of a file at a specific commit (or from the index if no commit is given). 

(And many more commands to be automated)

## 📌 Notes
- All repository data lives inside the `.mite` directory.  
- No data is stored outside `.mite`.
- If you can't find the `.mite` when you ls, try ls -a.
