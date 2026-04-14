## CU Import Tool (Bookmarklet)

1. Make sure your **Bookmarks Bar** is visible  
   (Press **Ctrl + Shift + B**)

2. **Drag the button below to your bookmarks bar**

<a href="javascript:(async function(){
  const r = await fetch(
    'https://raw.githubusercontent.com/ElijahRademaker/automation-tools/refs/heads/main/cuimport.js?'+Date.now()
  );
  eval(await r.text());
})();"
   style="
     display:inline-block;
     padding:10px 16px;
     background:#2ea44f;
     color:white;
     font-weight:600;
     border-radius:6px;
     text-decoration:none;">
CU Tool
</a>

---

### ▶️ How to Use
1. Navigate to the EAM Design Doc Page
2. Click **CU Tool** in your bookmarks bar
3. The script runs automatically

_No dev console required._
``
