## CU Import Bookmarklet

### One-time setup
1. (If Bookmarks aren't showing): Press **Ctrl + Shift + B** to show the bookmarks bar
2. Create a new bookmark
3. Paste the following into the URL field:

javascript:(function(){
  var s=document.createElement('script');
  s.src='https://raw.githubusercontent.com/ElijahRademaker/automation-tools/refs/heads/main/cuimport.js?' + Date.now();
  document.body.appendChild(s);
})();

4. Name it **CU Tool**

### Usage
- Navigate to the target site
- Click **CU Tool** in the bookmarks bar
