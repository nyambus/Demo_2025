   ```bash
   sudo nano /etc/apt/sources.list
   ```
   ```
   deb http://mirror.yandex.ru/debian/ bullseye main
   deb-src http://mirror.yandex.ru/debian/ bullseye main
   ```
   ```
   deb http://mirror.yandex.ru/debian-security bullseye-security main contrib
   ```
   ```
   deb [signed-by=/usr/share/keyrings/yandex.gpg] https://repo.yandex.ru/yandex-browser/deb/ stable main
   ```
   ```bash
   curl -fSsL https://repo.yandex.ru/yandex-browser/YANDEX-BROWSER-KEY.GPG | gpg --dearmor | tee /usr/share/keyrings/yandex.gpg > /dev/null


   curl -fsSL https://repo.yandex.ru/yandex-browser/YANDEX-BROWSER-KEY.GPG | gpg --dearmor -o /usr/share/keyrings/yandex.gpg
   ```
   ```bash
   sudo apt update
   ```

  
   ???
   ```bash
   apt search yandex-browser
   ```


