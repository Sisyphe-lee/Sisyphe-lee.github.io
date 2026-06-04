# Chunyang Li's Homepage

Static personal homepage for GitHub Pages.

Target repository:

```text
Sisyphe-lee/Sisyphe-lee.github.io
```

Target URL:

```text
https://sisyphe-lee.github.io/
```

## Local Preview

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Publish

After GitHub CLI authentication:

```bash
gh auth login
gh repo create Sisyphe-lee/Sisyphe-lee.github.io --public --source . --push
```
