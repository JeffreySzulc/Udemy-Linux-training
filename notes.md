# Notes from terminal commands

## 2025-04-15 
- Linux command syntax
- chmod basics for file and directory permissions
- Pushed from PowerShell, like a ninja

## 2025-04-16 
- User and group management
- File ownership and permissions
- Hard/symbolic links practice

## 2025-04-17 
- Learned about Access Control Lists (setfacl, getfacl)
- Practiced help commands (man, whatis, info)
- Ran into 'whatis' indexing issue — fixed with 'sudo mandb'

## 2025-04-22 – Linux Module 4 Progress Continued (67-69)

- ✅ Input and Output Redirects:
  - `>` overwrites, `>>` appends
  - `<` feeds input, `2>` redirects stderr
  - `&>` sends stdout + stderr to same file

- ✅ Standard Output to a File:
  - Learned `tee` to send output to file and screen at the same time

- ✅ Pipes `|`:
  - Used to chain commands together (e.g., `cat file.txt | grep "searchterm"`)

    Grinding hard through redirects, pipes, and command flow 🔁📄  
    Pushed from a keyboard held together by hope and tape.

## 2025-04-26 – Linux Fundamentals Module 4 (Lessons 72–77)

- Learned about `cut` for column/field extraction from text
- Practiced `awk` for pattern scanning and field processing
- Explored `grep` and `egrep` for searching file content
- Used `sort`, `uniq`, and `wc` to analyze and deduplicate text
- Got hands-on with `filters` to chain output between commands

## 2025-04-27 – Linux Fundamentals Module 4 (Lessons 78–84)

- Compared file differences using `diff` and `cmp`
- Practiced file archiving with `tar` and compression using `gzip` / `gunzip`
- Used `truncate` to shrink file size without editing contents
- Combined and split files using `cat`, `split`, and `csplit`
- Executed multiple commands in one line using `;`, `&&`, and `||`
- Noted the key differences between Linux and Windows command syntax
