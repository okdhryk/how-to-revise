# how-to-revise

## How to Install

```bash
git clone https://github.com/tsukuba-mas/how-to-revise.git
cd how-to-revise
```

## How to Compile

```bash
latexmkrc main.tex
```

## How to Push and Release on GitHub

An Example

```bash
# Push
git add .
git commit -m "your commit message"
git push origin origin-branch-name

# Make Release
git tag -a vX.X.X -m "your tag message"
git push origin vX.X.X
```
