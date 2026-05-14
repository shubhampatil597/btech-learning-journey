# Day 14 – Linux Environment Variables, PATH & Shell Variables

## 🧠 What are Environment Variables?

Environment variables are system-wide configuration values used by Linux to control system behavior.

They store important system information like:
- system paths
- user details
- configuration settings

---

## 🔹 Examples of Environment Variables

HOME=/home/user
PATH=/usr/bin:/bin:/usr/local/bin
USER=root
SHELL=/bin/bash

---

## 📌 Viewing Environment Variables

### Show all variables:
env

### Show specific variable:
printenv HOME

### Display variable using echo:
echo $HOME

---

## 🧭 What is PATH?

PATH is a special environment variable that stores directories where Linux searches for commands.

Example:
PATH=/usr/bin:/bin:/usr/local/bin

---

## ⚙️ How Linux Executes Commands

When you type a command like:
ls

Linux:
1. Checks directories in PATH
2. Searches for ls command
3. Executes it

---

## 🔹 Check Command Location

which ls

---

## 🔧 Modifying PATH (Temporary)

export PATH=$PATH:/myfolder

This adds a new directory to PATH temporarily.

---

# 🧩 Shell Variables

Shell variables are temporary variables that exist only in the current terminal session.

---

## 🔹 Example

name="Shubham"
echo $name

Output:
Shubham

---

## ⚠️ Important

- Shell variables are local to terminal
- They disappear when terminal closes

---

# 🚀 export Command

export is used to convert a shell variable into an environment variable.

---

## 🔹 Without export

name="Shubham"
Only current shell can use it.

---

## 🔹 With export

export name="Shubham"

Now:
- child processes can access it
- system-wide visibility increases (within session)

---

## 🧠 Simple Understanding

Shell Variable → Local to terminal  
export → Makes variable accessible to programs

---

## ☁️ Real World Use (Cloud/DevOps)

export is used for:
- API keys
- database URLs
- configuration settings
- deployment variables

Example:
export DATABASE_URL="localhost:3306"

---

## 🧭 Important Concept Connection

PATH itself is an exported environment variable.

That is why:
echo $PATH
works everywhere.

---

# 🔑 Key Concepts

- environment variables
- PATH
- shell variables
- export
- system configuration
- variable scope

---

# 🧪 Practical Tasks

## Task 1 — View all environment variables
env

---

## Task 2 — Check HOME variable
echo $HOME

---

## Task 3 — Create shell variable
name="MyLinux"

echo $name

---

## Task 4 — Use export
export name="MyLinux"

---

## Task 5 — View PATH
echo $PATH

---

## Task 6 — Check command location
which ls

---

## Task 7 — Modify PATH temporarily
export PATH=$PATH:/testfolder

echo $PATH

---

# 📝 Key Learnings

- Environment variables control system behavior
- PATH helps Linux locate commands
- Shell variables are temporary
- export makes variables accessible to programs
- Linux uses variables for configuration management

---

# 🌍 Real World Use

Environment variables are widely used in:
- Linux servers
- cloud environments (Azure, AWS)
- Docker containers
- CI/CD pipelines
- DevOps automation

---

# ❓ Revision Questions

1. What are environment variables?
2. What is PATH?
3. What is a shell variable?
4. What does export do?
5. Difference between shell variable and environment variable?
6. Why is PATH important?

---

# ⚡ Quick Revision

- env → shows variables  
- PATH → command search path  
- shell variable → temporary  
- export → makes variable global in session  
- which → shows command location  

---

# 🧠 Final Understanding

Linux system behavior depends on:

Environment Variables + PATH + Shell Scope