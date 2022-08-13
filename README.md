Hexo
A fast, simple & powerful blog framework, powered by Node.js.

Website | Documentation | Installation Guide | Contribution Guide | Code of Conduct | API | Twitter

NPM version Required Node version Build Status dependencies Status Coverage Status Gitter Discord Chat Telegram Chat FOSSA Status Contributor Covenant

Features
Blazing fast generating
Support for GitHub Flavored Markdown and most Octopress plugins
One-command deploy to GitHub Pages, Heroku, etc.
Powerful API for limitless extensibility
Hundreds of themes & plugins
Quick Start
Install Hexo

$ npm install hexo-cli -g
Install with brew on macOS and Linux:

$ brew install hexo
Setup your blog

$ hexo init blog
$ cd blog
Start the server

$ hexo server
Create a new post

$ hexo new "Hello Hexo"
Generate static files

$ hexo generate


hexo:
hexo g && hexo s
hexo d

git:
git add . && git commit -m "rename to xiaoyidianzi" && git push

推送命令
hexo d
1
2
扩展：

其中 hexo clean清除了你之前生成的东西，也可以不加。
hexo generate 顾名思义，生成静态文章，可以用 hexo g缩写
hexo deploy 部署文章，可以用hexo d缩写