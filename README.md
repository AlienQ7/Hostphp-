# 🚀 Hostphp  Setup Guide

This utility is very handy if you're doing some kind of **web development** from Termux, allowing you to easily manage your local PHP server.

---

## 🛠 Setup

### 1. Navigate to the `bin` directory

This ensures the script is placed where Termux looks for global commands.

```bash
cd $PREFIX/bin
```

### 2. Create the script file (hostp)
​Use a text editor (like nano) to create and open the new file.
```bash
cd hostp
```
​Note: Paste the content of your hostp script into this file, then save and exit nano.

### 3. Give Permission to excute
```bash
chmod +x hostp
```
✨ Usage
​### 4. Run the Host command
​You can now run hostp from any directory. 
```bash
hostp
```
The first time you run it, you'll be prompted to enter the file name you want to host (e.g., index.html or index.php).
### 5. Exiting the Interactive Prompt
After running, pressing Ctrl+C to exit the script.

### ​6. Killing the Running Server
​The server is designed to run in the background even if you close Termux. To stop it, use the specific kill command:
```bash
hostp kill
```
Untill you run this the server will be live,this is done so that you can edit your html/php file that is hosted and see the changes instanly in the browser by refreshing it. 
