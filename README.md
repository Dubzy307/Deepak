# Deepak
Installing claude code and codex in cursor IDE

-> Tools Installed
-> Cursor IDE
-> Claude Code (extension, installed manually via .vsix)
-> Codex (extension, installed manually via .vsix)
-> Node.js (installed as a dependency while troubleshooting CLI-based install attempts)
-> Visual studio (require to get .vsix cache of codex then locate it install it in cursor but couldn't find it in any folder)

**Steps Completed**
1. Installed Cursor IDE.
2. Opened Extensions in Cursor and searched for "Claude Code" — it did not appear in marketplace search results.
3. Searched for "Codex" — also did not appear in marketplace search results.
4. Researched why: Cursor no longer pulls extensions from the official Microsoft VS Code Marketplace becuase now it uses a separate registry called Open VSX instead, due to Microsoft's licensing terms restricting their marketplace to Microsoft's own products. Extensions not published to Open VSX don't show up in Cursor's built-in marketplace search.
5. Attempted to install Claude Code via its command-line tool (npm) as a first.
6. Installed Node.js, since it was a required dependency and it's not installed on my laptop.
8. Ran into further issues completing CLI-based install and login for both tools.
9. Switched approach: downloaded the `.vsix` extension files for both Claude Code and Codex directly from the Open VSX registry.
10. suggested by someone on the youtube so I Tried installing via drag-and-drop into Cursor's Extensions panel — this didn't work.
11. Installed both `.vsix` files manually instead, by pointing Cursor to the file path directly (using the "Install from VSIX" option / command line install pointing to the downloaded file path).
12. Both Claude Code and Codex installed successfully in Cursor after this.

 **Issues Ran Into and How I Solved Them**
1. Neither extension appeared in Cursor's Extensions marketplace search.
- Cause: Cursor uses Open VSX instead of the Microsoft VS Code Marketplace, and these extensions weren't showing up through Cursor's in-app search.
- Fix: downloaded the `.vsix` files directly from the Open VSX registry website instead of relying on in-app search.
  
2.  "npm" not recognized in terminal (during an earlier CLI-based install attempt).
-  Cause: Node.js wasn't installed on my machine.
-  Fix: installed Node.js LTS from nodejs.org and restarted the terminal to refresh PATH.

4. Choosing an authentication method for Claude Code.
- Had to pick between a Claude subscription, an Anthropic Console account, or 3rd party platforms (Bedrock/Vertex).
- opt for the Console/API option since it doesn't need money to install untill you use the credit 

 **Outcome**
Both Claude Code and Codex are successfully installed and logged in inside Cursor. Repository cloned to cursor
README.md written and done and changes committed and pushed to GitHub.

attaching the ss of both extension installed on the cursor
<img width="1348" height="820" alt="cursor ss" src="https://github.com/user-attachments/assets/e94bb135-fdee-42a1-82ed-74faa5fabd1c" />




