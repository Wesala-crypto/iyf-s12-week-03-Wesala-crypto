# Terminal Log — Week 3

This file records terminal commands practised during Week 3.

## Task 5.1: Terminal Navigation

- `mkdir ~/terminal-practice` — Created the practice folder.
- `cd ~/terminal-practice` — Entered the practice folder.
- `pwd` — Displayed the current directory.
- `ls` — Listed directory contents.
- `cd ~/Documents` — Navigated to Documents.
- `cd ..` — Moved to the parent directory.
- `cd ~` — Returned to the home directory.
- `mkdir -p my-project/src/{css,js,images} my-project/{docs,tests}` — Created the required directory structure.
- `touch my-project/README.md` — Created the README file.
- `find my-project -print` — Listed the project structure.

## Task 5.2: File Operations

- `touch index.html` — Created an empty HTML file.
- `cat index.html` — Displayed the file contents.
- `cp index.html backup.html` — Copied the file.
- `mv backup.html my-project/docs/` — Moved the copy into the docs directory.
- `mv index.html home.html` — Renamed the original file.
- `rm home.html` — Deleted the renamed file.
- `cp -r my-project/src/ my-project/src-backup/` — Copied a directory and its contents.
- `mv my-project/src-backup/ my-project/archive/` — Renamed the copied directory.
- `rmdir my-project/archive/` — Attempted to remove a non-empty directory; the command failed as expected.
- `rm -r my-project/archive/` — Removed the directory and its contents.

## Task 5.3: Useful Terminal Commands

- `find . -name "*.html"` — Found HTML files in the portfolio.
- `grep -rl "contact" .` — Searched recursively for files containing "contact".
- `wc -l styles.css` — Counted CSS lines.
- `history | tail -10` — Displayed the last ten terminal history entries.
- `grep "class" index.html` — Searched for "class" in the HTML file.
- `grep -r "button" ./src/` — Attempted a recursive search; the src directory did not exist in the portfolio.
- `head -10 styles.css` — Displayed the first ten CSS lines.
- `tail -10 styles.css` — Displayed the last ten CSS lines.
- `wc index.html` — Counted lines, words and bytes in the HTML file.

## Task 5.4: Shell Script

- `touch new-project.sh` — Created the shell script file.
- `chmod +x new-project.sh` — Made the script executable.

## Notes

Commands were practised in Git Bash on Windows. Directory and file operations were performed in the separate terminal-practice folder to protect the portfolio.
