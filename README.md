# Linux Mint Customization Project

## Project Overview
This project involves exploring, modifying, and rebuilding the **Linux Mint** operating system. The main objective was to gain hands-on experience with Linux source code, implement small but meaningful customizations, and test the changes in a virtual environment.

### Key Features
- **Custom Pop-up Messages:**  
  - On system startup, a pop-up message displays:  
    `"Welcome from Aaron, Prachun, and Suvankar"`
  - After clicking **"Okay"**, a second message appears:  
    `"Hi! Do you want to see us?"`

- **Dynamic Wallpaper Change:**  
  - The desktop wallpaper changes automatically after interacting with the pop-up messages.

### Tools and Environment
- **Host OS:** Windows 10  
- **Guest OS:** Linux Mint 21 “Vanessa” (VirtualBox VM)  
- **Tools Used:** Git, GCC, Make, Vim/Nano, VS Code, VirtualBox  
- **Dependencies:** `build-essential`, `libc6-dev`, `libgtk-3-dev`, kernel headers  

### Implementation Steps
1. **Cloning the Linux Mint source code:**  
   ```bash
   git clone https://github.com/linuxmint
