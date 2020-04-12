---
id: doc2
title:  How to build this website?
---

---
https://www.youtube.com/watch?v=dn4dgA51WNg Build and deploy Docusaurus
---
** yarn run build 
 git remote add origin https://github.com/chinajinwanjun/test-site.git
git commit  -m "first commit"
git push origin master   
git checkout  -b gh-pages
```
git add -f .\build\ 
 git commit -m "init"
 git  subtree  push --prefix build origin gh-pages

  master --

 ```