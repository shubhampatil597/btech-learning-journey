# Day 17 – Linux Shell Scripting Basics

# What is Shell Scripting?

Shell scripting means writing Linux commands inside a file for automatic execution.

Used for:
- automation
- backups
- monitoring
- administration

---

# Bash

Bash = Bourne Again Shell

It interprets Linux commands.

---

# Script File

Shell scripts usually use:
.sh

Example:
hello.sh

---

# First Script

#!/bin/bash
echo "Hello Linux"

---

# Run Script

bash hello.sh

---

# Shebang

#!/bin/bash

Tells Linux which interpreter to use.

---

# Variables

name="Linux"

echo $name

---

# User Input

echo "Enter name:"
read name

echo "Hello $name"

---

# Comments

# This is comment

Comments are ignored during execution.

---

# Executable Permission

chmod +x hello.sh

Run directly:
./hello.sh

---

# Key Learnings

- shell scripts automate Linux tasks
- bash executes scripts
- variables store data
- read accepts user input
- chmod gives executable permission