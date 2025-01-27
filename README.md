# WishHistoryLinkGrabber
History link grabber for Genshin Impact

# How to Extract Genshin Impact Wish History Link  

Follow the steps below to extract your Genshin Impact wish history link using PowerShell:  

### Steps  

1. Open **Genshin Impact** on your PC.  
2. Go to the **Wish History** page and wait for it to load completely.  
3. Minimize the game and go back to Windows.  
4. Open the Start menu, search for **PowerShell**, and open **Windows PowerShell**.  
5. Copy the following command and paste it into the PowerShell window:  

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex "&{$((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/sarpowsky/WishHistoryLinkGrabber/refs/heads/main/historykey.ps1'))} global"
6. Hit ENTER to execute the command. The wish history link will be automatically copied to your clipboard.
7. Paste the copied link into the required field.
