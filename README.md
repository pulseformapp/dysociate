# dλsociate

**An open-source thread editor that fits an entire conversation inside one HTML file.**

*created by luna love, lunasoft λ 2026*

dλsociate brings the look of an old terminal to a simple desktop editor. Write a post, add a picture, and save the thread as a single HTML file. The posts, images, replies, and browser editor all travel inside that file.

Send it to someone and they can open it in a compatible browser, add a reply, and save an updated copy. Each copy has its own history. Pass the newest file back to keep the conversation going.

## Install on Windows

1. Open **Releases** on this repository.
2. Download and run `dysociate-1.5.6-setup.exe`.
3. Open **dλsociate** from the Windows Start menu and review the two startup agreements.

The desktop app runs offline on 64-bit Windows 10 or 11. For a portable copy, extract `dysociate-1.5.6-portable-windows-x64.zip` and open `dysociate/dysociate.exe`.

## Make your first thread

1. Write something in **Your Text**. Use **Choose image** if you want to add a picture.
2. Click **Add post**, then **Save**. Choose where to keep your `index.html`.
3. Use **Preview** to see the thread in your browser. Use **Share** to copy the file or create an email draft with the HTML attached.

Press **Alt+Enter** to switch between fullscreen and windowed mode. **F1** opens the offline manual.

## Use the browser edition

Download and extract `dysociate-1.5.6-browser.zip` from **Releases**. Open `Browser/index.html` in a full browser and choose **Open HTML** to load a saved thread.

You can also host that browser editor on a static HTTPS site. This gives phone users a way to open the downloaded thread when their mail app only shows an attachment preview.

## Run from source

On Windows with Python 3.11 or newer, open PowerShell in the repository folder and run:

```powershell
& '.\run_dysociate.ps1'
```



## License

Copyright © 2026 Luna Love ~ LunaSoft. The source is available under [GPL-3.0-or-later](LICENSE). The matching source, build scripts, and documentation are included with the release. Your posts and pictures remain yours.
