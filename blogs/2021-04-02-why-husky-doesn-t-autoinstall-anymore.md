---
title: "Why husky doesn't autoinstall anymore"
url: "https://blog.typicode.com/posts/husky-git-hooks-autoinstall/"
date: "2021-04-02"
feed_url: "https://blog.typicode.com/index.xml"
---
Another change with the new husky is that it doesn’t autoinstall Git hooks anymore. Instead, the new recommended way is to have a prepare* script in your package.json: { "prepare": "husky install" } Let’s see why. (*) There’s an exception for Yarn 2 though, see docs.
