# teste-calina-hugo-theme

## hOW TO

1. Create your Site

```bash
hugo new site yourBraveNameSite
cd yourBraveNameSite
git init
git submodule add https://github.com/cromozooom/calina.git themes/calina
echo "theme = 'calina'" >> hugo.toml hugo server
```

2. copy these files (from the theme) to root

- hugo_stats.json
- hugo.toml
- LICENSE
- netlify.toml
- package.hugo.json
- package.json
- postcss.config.js
- tailwind.config.js
