
# Editing

the `_index.md` file in the `bluestonenumbers` directory is the main content.

Images are added to `bluestonehousenumbers/static/images` directory

# Generate site:

```
> cd bluestonenumbers
> hugo build --gc --minify --baseURL "https://apioli.github.io"
```

# Preview site locally

```
> cd bluestonenumbers
> hugo server
```


# Copy to github pages dir
```
> cp -r public/* ../docs
```

then normal git add, commit, push to github.