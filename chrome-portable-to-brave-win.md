Migrate/Switch from Google Chrome Portable to Brave on Windows:

1. Open **File Explorer**
2. Go to `%LocalAppData%`
3. Create folder `Google` > `Chrome` > `User Data`
4. Open **Chrome Portable** and navigate to `chrome://version/#:~:text=Profile%20Path`
5. Look for the `Profile Path` field*, copy profile folder & `Local State` file to `%LocalAppData%\Google\Chrome\User Data`
6. Open **Brave** and navigate to `brave://settings/importData`
7. Select profile and click **Import**

ㅤ

Saved passwords:
1. Open **Chrome Portable** and navigate to `chrome://password-manager/settings`
2. Look for the `Export passwords` field and click **Download file**
3. Open **Brave** and navigate to `brave://password-manager/settings`
4. Look for the `Import passwords` field and click **Select file**
5. Check `Delete Chrome Passwords.csv, so others who use this device can't see your passwords` and click **View passwords**

ㅤ

\* = The Default directory is for the primary profile. If you have multiple profiles, they will be listed under separate directories like Profile 1, Profile 2, etc.
