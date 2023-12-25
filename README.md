# micheleux.github.io

- [Hugo](https://gohugo.io/)
- [Hugo Themes > Hallo](https://github.com/EmielH/hallo-hugo)
- [Emoji Favicons > Purple Heart](https://favicon.io/emoji-favicons/purple-heart)

## Build

```bash
# clone
git clone git@github.com:micheleux/micheleux.github.io.git
# build
hugo
```

## Server

```bash
hugo server --disableFastRender
```

## Publish

```bash
# remove old content
rm -rf docs/*
# build new content
hugo --ignoreCache -d docs
# commit new content
git add docs/*
git commit -m "publish: `date --rfc-3339=seconds`"
```
