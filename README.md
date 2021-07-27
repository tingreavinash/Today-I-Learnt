## TIL: 27-07-2021
**IntelliJ Handy Shortcuts**
* Bookmark files/lines on your IDE<br>
  * To add/remove a bookmark to a file press `Ctrl+Shift+F11` key.
  * To view all your bookmarked files press `Shift+F11`.
* Recently opened/edited files: `Ctrl+E`
* Find in Files: `Ctrl+H`
* Choose the content to Paste: `Ctrl+Shift+V`
---
**Docker Caching - To avoid invalidating the cache**
 1. Start your Dockerfile with commands that are less likely to change
 2. Place commands that are more likely to change (like COPY . .) as late as possible
 3. Add only the necessary files (use a .dockerignore file)
