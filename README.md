# Store-Github-password

### How to make git cache your password on GitHub

### Set git to use the credential memory cache

```
$git config --global credential.helper cache
```

### Set the cache to timeout after 1 hour (setting is in seconds)

```
$git config --global credential.helper 'cache --timeout=3600'
```