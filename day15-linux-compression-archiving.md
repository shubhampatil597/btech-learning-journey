# Day 15 – Linux Compression & Archiving

# Why Compression Important?

Linux systems use compression for:
- backups
- log storage
- software packages
- efficient transfer

---

# Archive vs Compression

## Archive
Combines multiple files into one file.

Example:
backup.tar

---

## Compression
Reduces file size.

Example:
file.txt.gz

---

# tar Command

tar creates archives.

## Create archive
tar -cvf notes.tar folder

## Extract archive
tar -xvf notes.tar

---

# gzip Command

gzip compresses files.

## Compress file
gzip file.txt

## Decompress file
gunzip file.txt.gz

---

# tar + gzip

## Create compressed archive
tar -czvf backup.tar.gz folder

## Extract compressed archive
tar -xzvf backup.tar.gz

---

# zip Command

## Create zip
zip notes.zip file.txt

## Compress folder
zip -r project.zip folder

---

# unzip Command

## Extract zip
unzip notes.zip

---

# Key Learnings

- tar creates archives
- gzip compresses files
- tar.gz combines archive + compression
- zip/unzip manage compressed packages