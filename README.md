# howtodiy blog

## Setup

Build public files

```bash
hugo
cd public
git commit -am "code"
git push origin main
```

Update Theme

```bash
hugo mod clean
hugo mod get -u github.com/chipzoller/hugo-clarity
```

Update all hugo modules
```bash
hugo mod get -u ./...
```

Old way of adding git submodule

```bash
git submodule add -b main https://github.com/howtodiy/howtodiy.github.io.git public
git submodule update --init --recursive
```

Start server
```bash
hugo server
```

