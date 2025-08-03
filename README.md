    Since hugo had a major update, I'm planning to migrate to a better templating scheme.
    So here we are..

Installing the theme:

```bash
hugo new site quickstart
cd quickstart
git init
git submodule add -b hugo_update https://github.com/razzat008/meow.git themes/meow
echo "theme = 'meow'" >> hugo.toml
hugo serve --noHTTPCache --disableFastRender
```

Then follow along this:\
[https://gohugo.io/getting-started/quick-start/](https://gohugo.io/getting-started/quick-start/) 


I couldn't get these working:\
❌ lastmod value using git commit
<!-- ✅❌  -->


## adding contents,menus
- check `hugo.toml`
- look into the `content/` directory
