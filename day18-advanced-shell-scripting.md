# Day 18 – Advanced Shell Scripting

# Conditions

Conditions allow scripts to make decisions.

---

# if Statement

if [ condition ]
then
 command
fi

---

# Comparison Operators

-eq → equal  
-ne → not equal  
-gt → greater than  
-lt → less than  
-ge → greater/equal  
-le → less/equal  

---

# if-else

if [ condition ]
then
 command
else
 command
fi

---

# elif

Used for multiple conditions.

---

# Loops

Loops repeat commands automatically.

---

# for Loop

for i in 1 2 3
do
 echo $i
done

---

# while Loop

count=1

while [ $count -le 5 ]
do
 echo $count
 count=$((count+1))
done

---

# Script Arguments

$1 → first argument  
$2 → second argument

Example:
bash test.sh Linux

---

# Automation Script Example

mkdir backup
cp file.txt backup

echo "Backup completed"

---

# Key Learnings

- conditions make decisions
- loops automate repetition
- arguments pass values
- scripting enables automation