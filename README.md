# Simple URL redirect  tool

#### This tool just for myself wants to direct open certain notes in local with the Obsidian link.
#### Convenient for me to manage tasks on Notion.
#### Combine with HTTP Web Server can become a simple URL redirect tool.

Fast Example:
1. Git clone this codebase to a local folder.
2. Chrome install plugin "Web Server for Chrome"
   * https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb
3. Choose the folder which placed the code folder.
4. Access http://127.0.0.1:8887 (Port Number based on your setting), can see the error page.
5. Put the URL you want to redirect after http://127.0.0.1:8887 with prefix "?", which can redirect to a certain page.
   * http://127.0.0.1:8887?https://www.google.com.tw/
6. Also can access other app URLs, like Obsidian link
   * http://127.0.0.1:8887?obsidian://open?vault=Arcadyan&file=test1