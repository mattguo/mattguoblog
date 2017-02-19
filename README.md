# Matt Guo blog

## Setup
Install hexo, initialize the site, and create git repo
```
npm install hexo-cli -g
hexo init myblog
cd myblog
git init
```
## Add theme
Git fork a hexo theme and add it as a git submodule
```
git submodule add git@github.com:mattguo/hexo-theme-bootstrap-blog.git themes/bootstrap-
blog
```
Then in **\_config.yml**, change to use the **bootstrap-
blog** theme.

## Start
Then write some articles, check them into the main git repo, and check the theme hack into the git submodule.
