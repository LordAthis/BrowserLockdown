**Disable Autoplay on Browser**

<details>
<summary>Google Chrome or Opera</summary>
ㅤ

[ref](https://developer.chrome.com/blog/autoplay/#developer_switches)

ㅤ

How to:

1. **Right-click** on Chrome shortcut and select `Properties`
2. Go to `Shortcut` tab
3. In the Target field, add flag after **chrome.exe** portion, outside the quotes. For example: 
```
"C:\Program Files\Google\Chrome\Application\chrome.exe" --disable-features="PreloadMediaEngagementData, MediaEngagementBypassAutoplayPolicies"
```
4. Click OK
5. Open **Chrome**

ㅤ
</details>

<details>
<summary>Microsoft Edge</summary>
ㅤ

1. Open **Microsoft Edge**
2. In the address bar, type `edge://flags` and press **Enter**
3. In the search box, type `autoplay`. You should find a single entry: `Show block option in autoplay settings`
4. Use the dropdown next to it to change the setting to "Enabled"
5. Click **restart** button for the changes to take effect.
6. In the address bar, type `edge://settings/content/mediaAutoplay` and press Enter.
7. Under **Control if audio and video play automatically on sites** section, set option to `Block` if available.
8. Restart the browser for the changes to take full effect (optional).

ㅤ
</details>

<details>
<summary>Brave</summary>
ㅤ

https://community.brave.com/t/277662/2

ㅤ
</details>

<details>
<summary>Mozilla Firefox</summary>
ㅤ

https://support.mozilla.org/en-US/kb/block-autoplay

ㅤ
</details>
