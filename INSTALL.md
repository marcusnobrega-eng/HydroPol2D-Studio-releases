# Installing HydroPol2D Studio

You need two things: the installer file for your computer, and your license code. The license code is a long line of text that starts with `HP2D1-`.

## Mac (Apple Silicon)

1. Unzip `HydroPol2D-Studio-macOS-arm64.zip`.
2. Drag **HydroPol2D Studio** into your **Applications** folder.
3. Double-click it. The first time, macOS says it cannot check the app for malicious software. Click **Done**.
4. Open **System Settings › Privacy & Security**. Scroll down to the message about HydroPol2D Studio and click **Open Anyway**. Confirm with your password.
5. The license window opens. Paste your code and click **Activate**.

You only do steps 3 and 4 once.

If you prefer Terminal, this command lets macOS open the app without step 4:

```bash
xattr -dr com.apple.quarantine "/Applications/HydroPol2D Studio.app"
```

## Windows (64-bit)

1. Unzip `HydroPol2D-Studio-Windows-x64.zip` into a folder you keep, for example `Documents\HydroPol2D Studio`.
2. Double-click **HydroPol2D Studio.exe**.
3. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.
4. The license window opens. Paste your code and click **Activate**.

## About your license

- Your code works on any computer you install Studio on. Enter the same code on each one.
- Studio checks the code on your computer. It does not need the internet for this.
- Studio tells you when fewer than 30 days are left. For a new code, contact Marcus N. Gomes Jr.
- Studio keeps the code here:
  - Mac: `~/Library/Application Support/HydroPol2D Studio/license.txt`
  - Windows: `%APPDATA%\HydroPol2D Studio\license.txt`

  To enter a different code, delete that file and open Studio again.
- Keep your computer's date correct. Studio refuses to start if the date is set back before the last time you used it.
