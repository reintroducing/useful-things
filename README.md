# Useful Things
A collection of snippets that I find useful and wanted to document somewhere so I don't forget them (and not have them astray all over my file system somewhere so I forget I have them).

## Chrome

### Inspect and style an element in DevTools that normally disappears when inactive
[Original Post](https://elijahmanor.com/inspect-tricky-elements/)
```js
setTimeout(() => {debugger}, 3000);
```

## Git

### Move repo remote from one provider to another
GitLab to GitHub, for example.
```bash
git remotes remove origin
git remotes add origin [url-to-repo].git
```
