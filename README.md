# The What?

This is a [Hugo](gohugo.io) template made to make a simple hugo webpage that is
both minimalistic and easy to configure.

My [website](https://razzat008.github.io) is built using this theme.

# How to use?

Just like any other Hugo theme, you can clone it to your machine and use it
right away.

## Prerequisites

- hugo
- somewhat knowledge of markdown

## Steps: To install

Create a hugo site

```bash
hugo new site mysite
```

Go into the directory

```bash
cd mysite
```

Initialize an empty git repository

```bash
git init
```

Add this theme into your website directory

```bash
git submodule add https://github.com/razzat008/meow themes/meow
```

Set the theme to _meow_ in _hugo.toml_

```bash
echo "theme='meow'" >> hugo.toml
```

## More

You can check out the _example/_ directory see list of available parameters for
this site.

To add content refer to
[this](https://gohugo.io/getting-started/quick-start/#add-content) official
documentation from Hugo.

Use `generate_icons.sh` to generate favicons for your webpage.

## To learn Hugo check these out:

- https://youtu.be/KwkjqMs7ZYI : Eric Murphy
- https://youtu.be/ZFL09qhKi5I : Luke Smith

## Contributing

I want this template to be minimal as possible. So, if you have any awesome idea
to make this theme better, feel free to open a PR.
