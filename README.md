## How to install:

1. Uninstall original Wino Mail
2. Download [the public certificate](https://raw.githubusercontent.com/reddxae/Wino-Mail/refs/heads/releases/PublicCertificate.cer)
3. Run in PowerShell as an Administrator :
   ```powershell
   Import-Certificate -FilePath "PublicCertificate.cer" -CertStoreLocation "Cert:\LocalMachine\TrustedPeople"
   ```
4. Download [Scoop](https://scoop.sh)
5. Run:
   ```
   scoop bucket add reddxae-wino https://github.com/reddxae/Wino-Mail
   ```
6. Run:
    ```
    scoop install wino-mail
    ```

![halal](https://github.com/user-attachments/assets/5eab27ac-57cc-4cc5-8b4f-4ca525dfc4a9)
