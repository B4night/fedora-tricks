



At some circumstances, we may download some executable programs like `.Appimage` or binary files. In order to find these programs in both `control` and `search light`, we need to creat entries for these files.

PS: `search light` is a useful extension, recommend.



1. First, cd to `~/.local/share/applications`

2. create `<app name>.desktop`

3. enter info. e.g.

   ``` shell
   [Desktop Entry]
   Version=1.0
   Encoding=UTF-8
   Type=Application
   Name=typora
   NoDisplay=true
   Exec=typora
   ```

4. `desktop-file-validate <app name>desktop`



Now we can see these apps in `control`.