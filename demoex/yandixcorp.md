   ```bash
   sudo nano /etc/apt/sources.list
   ```
   ```
   deb [signed-by=/usr/share/keyrings/yandex.gpg] https://repo.yandex.ru/yandex-browser/deb/ stable main
   ```
   ```bash
   curl -fSsL https://repo.yandex.ru/yandex-browser/YANDEX-BROWSER-KEY.GPG | gpg --dearmor | tee /usr/share/keyrings/yandex.gpg > /dev/null
   ```
   ```bash
   sudo apt update
   ```


