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
