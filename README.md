# Origami Lab Handbook

## Work locally

The easiest way is probably to use the mkdocs Docker image:

```shell
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

See (the docs)[https://squidfunk.github.io/mkdocs-material/creating-your-site/] for more information
