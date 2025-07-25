# To-unzip-files-in-Kali-Linux
To **unzip files in Kali Linux**, it depends on the file format. Here's a quick guide for common archive types:

---

### 🔹 **1. Unzip `.zip` files**

```bash
unzip filename.zip
```

**Install unzip (if not installed):**

```bash
sudo apt update && sudo apt install unzip -y
```

---

### 🔹 **2. Unpack `.tar.gz` or `.tgz`**

```bash
tar -xzf filename.tar.gz
```

---

### 🔹 **3. Unpack `.tar.bz2`**

```bash
tar -xjf filename.tar.bz2
```

---

### 🔹 **4. Unpack `.tar.xz`**

```bash
tar -xJf filename.tar.xz
```

---

### 🔹 **5. Extract `.7z` files**

```bash
7z x filename.7z
```

**Install `p7zip` tools:**

```bash
sudo apt install p7zip-full -y
```

---

### 🔹 **6. Extract `.rar` files**

```bash
unrar x filename.rar
```

**Install unrar:**

```bash
sudo apt install unrar -y
```

---

### ✅ Tip: Extract to a specific directory

```bash
unzip filename.zip -d /path/to/dir
tar -xzf filename.tar.gz -C /path/to/dir
```

Let me know the file type if you want a command for it specifically.
To **zip any file or folder in Kali Linux**, you can use the `zip` or `tar` command depending on the format you want.

---

### 🔹 **1. Create a `.zip` file**

```bash
zip output.zip file1 file2 file3
```

**Example:**

```bash
zip myfiles.zip notes.txt image.png
```

✅ To **zip a folder** (recursively):

```bash
zip -r output.zip foldername/
```

**Example:**

```bash
zip -r myfolder.zip Documents/
```

**Install `zip` if needed:**

```bash
sudo apt install zip -y
```

---

### 🔹 **2. Create a `.tar.gz` archive (common in Linux)**

```bash
tar -czf output.tar.gz file_or_folder
```

**Examples:**

```bash
tar -czf archive.tar.gz myfile.txt
tar -czf folder_backup.tar.gz myfolder/
```

---

### 🔹 **3. Create a `.7z` archive (with 7-Zip)**

```bash
7z a output.7z file_or_folder
```

**Install 7z if not installed:**

```bash
sudo apt install p7zip-full -y
```

---

Let me know your preferred format or file type (e.g., `.zip`, `.tar.gz`, `.7z`) if you want a specific command.

