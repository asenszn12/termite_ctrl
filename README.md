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

### `mite-show [commit_index]:[file name]`
Displays the contents of a file at a specific commit (or from the index if no commit is given). 

### `mite-rm [--force] [--staged] <filenames...>`
Removes files from the repository.  
- **Default:** Removes file from both the index *and* the working directory.  
- **`--staged`:** Removes only from the index (keeps the working file).  
- **`--force`:** Overrides safety checks and removes files even if changes would be lost.  
- ALSO prevents accidental data loss by default (warns if file differs between index, working directory, or repository).

### `mite-status`
Displays the status of files in the working directory, index, and repository.  
It shows which files are staged for commit, modified, or untracked.  
## 📌 Notes
- All repository data lives inside the `.mite` directory.  
- No data is stored outside `.mite`.
- If you can't find the `.mite` when you ls, try ls -a.
