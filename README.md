# Firefox Flatpak Repo
### For development purpose only
---
* Add remote

    * on system
    ```
    flatpak remote-add --no-gpg-verify firefox 
    https://blog.kukuh.syafaat.id/firefox-flatpak-repo/repo/
    ```

    * on user
    ```
    flatpak remote-add --user --no-gpg-verify firefox 
    https://blog.kukuh.syafaat.id/firefox-flatpak-repo/repo/
    ```

* Install

    * on system
    ```
    sudo flatpak install firefox org.mozilla.Firefox
    ```

    * on user
    ```
    flatpak install --user firefox org.mozilla.Firefox
    ```

* Run
```
flatpak run org.mozilla.Firefox
```

### TODO
* GPG signatures
* Flatpakref files

---
Flatpak source code: https://github.com/cho2/org.mozilla.Firefox
