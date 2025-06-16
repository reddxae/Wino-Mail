**If you have found this casually then it is not for you.**

## How to install

> [!WARNING]
> Be aware of the security implications of importing a certificate: this opens you up to man-in-the-middle attacks by anyone with the private version of it. Also, this certificate won't be revoked if it's compromised 'case it is self-signed. Don't forget to delete it if you decide to stop using the app.

1. Install dependencies from the latest release if needed. Note that you must install the [.NET 9.0 Desktop Runtime](https://versionsof.net/core/9.0) in order to run the app.
2. Uninstall original Wino Mail if you have it
3. Download [the public certificate](https://raw.githubusercontent.com/reddxae/Wino-Mail/refs/heads/master/PublicCertificate.cer)
4. Run in PowerShell as an Administrator:
   ```powershell
   Import-Certificate -FilePath "PublicCertificate.cer" -CertStoreLocation "Cert:\LocalMachine\TrustedPeople"
   ```
5. Download [Scoop](https://scoop.sh)
6. Run:
   ```
   scoop bucket add reddxae-wino https://github.com/reddxae/Wino-Mail
   ```
7. Then run:
    ```
    scoop install wino-mail
    ```

[![halal](https://github.com/user-attachments/assets/5eab27ac-57cc-4cc5-8b4f-4ca525dfc4a9)](https://github.com/user-attachments/assets/ca341a8d-6538-4767-899f-e7e3707512ca)
