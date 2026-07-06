this repositry contain all the  Assignment commnds and there screen shot.
# Linux Basic Commands Assignment

1. Creating and Renaming Files/Directories

 Create a directory, create a file inside it, and rename the file.

'''
mkdir test_dir
touch test_dir/example.txt
mv test_dir/example.txt test_dir/renamed_example.txt
```

---
 2. Viewing File Contents

 Display the complete file, the first 5 lines, and the last 5 lines of a file.

```bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

---

3. Searching for Patterns
Search for lines containing a specific word in a file.

```bash
grep "root" /etc/passwd
```

---

4. Zipping and Unzipping

 Compress a directory into a ZIP file and extract it to another directory.

```bash
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir
```

---

5. Downloading Files

 Download a file from the internet using a URL.

```bash
wget https://example.com/sample.txt
```

---

6. Changing Permissions

 Create a file and make it read-only for all users.

```bash
touch secure.txt
chmod 444 secure.txt
```

---

7. Working with Environment Variables

 Create an environment variable and assign it a value.

```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```
