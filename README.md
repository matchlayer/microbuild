# Microbuild

Scripts to build SCSS modules into CSS and stats.

## Install

```sh
npm install --save-dev microbuild autoprefixer postcss-scss
```

```sh
cat << EOF > ./.browserslistrc
> 1%
last 2 versions
not dead
EOF
```

```sh
cat << EOF > ./.postcssrc.json
{
  "syntax": "postcss-scss",
  "plugins": {
    "autoprefixer": {}
  }
}
EOF
```
