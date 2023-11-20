[Information Source](https://askubuntu.com/questions/237063/force-file-extension-to-open-with-specific-app-extensions-like-exe-jpg-mp4)

# mimeopen command

use `mimeooen -d filename.exe` to determine how to open this file.

## e.g.

``` shell
$ mimeopen -d README.md 
Please choose a default application for files of type text/markdown

        1) opt  (opt-usercreated-1)
        2) Okular  (okularApplication_md)
        3) Visual Studio Code  (code)
        4) GVim  (gvim)
        5) LibreOffice Writer  (libreoffice-writer)
        6) Okular  (okularApplication_txt)
        7) Text Editor  (org.gnome.TextEditor)
        8) gedit  (org.gnome.gedit)
        9) KWrite  (org.kde.kwrite)
        10) Open on connected device via KDE Connect  (org.kde.kdeconnect_open)
        11) Red Hat GES BeyondTrust Helper  (redhat-internal-remote-assistance-helper)
        12) Other...

use application #12
use command: /opt/typora/Typora
Opening "README.md" with opt  (text/markdown)
```

