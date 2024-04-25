---
title: chirpy local
date: 2024-04-25 16:43 -0500
categories: [Site Organization]
tags: [Theme help]
---

If you are using the chripy starter theme locally and you are getting an error after creating posts do the following:
1. In your sidebar (using Visual studio code) find the _plugins folder and delete it
2. run the following command ```bundle exec jekyll clean``` as this will delete the _site folder
3. run the command ```bundle exec jekyll serve```

You now have an active site with posts!


