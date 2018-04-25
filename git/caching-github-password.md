# Caching Your Github Password on git

To cache your Github password on git, use the following command on terminal:-

`git config --global credential.helper osxkeychain`

To delete your password from cache, use this:-

```
git credential-osxkeychain erase
host=github.com
protocol=https
[Press Return]
```

Visit [this page](https://help.github.com/articles/caching-your-github-password-in-git) for other Operating Systems.

