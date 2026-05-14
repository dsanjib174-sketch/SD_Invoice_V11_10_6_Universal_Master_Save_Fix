# SD Invoice V11.10.6 Universal Master Save Fix

Replace BOTH:
- server.js
- public/index.html

This build fixes Customer/Product save by using a new universal save API:
- /api/universal/customers/save
- /api/universal/products/save

It bypasses old broken save functions and old role-blocking issues.

Render:
1. Upload server.js
2. Upload public/index.html
3. Commit changes
4. Manual Deploy > Deploy latest commit
