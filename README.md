## 🚀 CU Import Tool (Bookmarklet)

### One‑time setup

1. Show the bookmarks bar (**Ctrl + Shift + B**)
2. Create a new bookmark (any page)
3. Edit the bookmark and paste **this entire line** into the URL field:

```text
javascript:(function(){var s=document.createElement('script');s.src='https://raw.githubusercontent.com/ElijahRademaker/automation-tools/refs/heads/main/cuimport.js?'+Date.now();document.body.appendChild(s);})();
