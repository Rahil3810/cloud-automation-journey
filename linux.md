# Linux Fundamentals

## Environment
- Windows Subsystem for Linux (Ubuntu)
- Virtualization enabled in BIOS

---

## File & Directory Commands

### mkdir
Creates a directory.

### rm
Removes files.

### rm -rf
- r = recursive (delete folders and contents)
- f = force (no confirmation)

---

## Navigation

### ls -la
Lists all files including hidden files.

### cd
Change directory.

### cd ..
Go back one directory level.

---

## Permissions

Linux uses three permission types:
- r (read) = 4
- w (write) = 2
- x (execute) = 1

Permission categories:
- Owner
- Group
- Others

### chmod 755
Owner: rwx (7)
Group: r-x (5)
Others: r-x (5)

### chmod 655
Owner: rw- (6)
Group: r-x (5)
Others: r-x (5)

Used when execution should be restricted.

---

## History & Pipes

### history
Displays command history.

### history | tail -n 10
Shows last 10 commands.

Pipe (|) sends output of one command as input to another.

---

## grep
Used to search text inside files or output.

---

## What I Practiced
- Created directory structure
- Removed directories using rm -rf
- Modified permissions using chmod
- Used history with tail
- Navigated entirely using terminal
