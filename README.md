# VIP-BiblioTECH  

## Git Command Guide  

### Cloning the Repository  
To download the repository onto your computer, run:  
```bash
git clone https://github.gatech.edu/aalamin3/VIP-BiblioTECH
```
Then, initialize the local repository:  
```bash
git init
```

### Pulling Changes from the Cloud  
Before making any changes, always pull the latest updates:  
```bash
git pull
```

### Pushing Your Changes  

1. **Stage Your Changes**  
   - **Stage all changes:**  
     ```bash
     git add .
     ```
   - **Stage specific files:**  
     ```bash
     git add example1.txt example2.java
     ```
   **⚠ Important:** Always pull the latest changes (`git pull`) before adding files to avoid merge conflicts.  

2. **Commit Your Changes**  
   Add a commit message describing your changes:  
   ```bash
   git commit -m "Your descriptive commit message here"
   ```

3. **Push to the Cloud**  
   Finally, push your changes to the repository:  
   ```bash
   git push origin main
   ```
   Your changes should now be available on the cloud!  

### Additional Notes  
- The first time you push changes, Git may prompt you to log in. Use your Georgia Tech GitHub login.  
- Check out this helpful guide if you need more help: [Git Guide](https://rogerdudler.github.io/git-guide/)
- You can also use the following command to access Git's built-in help documentation:  
  ```bash
  git --help
  ```

If you need any help, feel free to reach out to me! 🚀  
