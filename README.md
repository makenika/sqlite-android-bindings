### Exporting from fossil to git

```bash
# Assuming sqlite-android-bindings.fossil is fetched
cd sqlite-android-bindings/ # git repo
fossil export --git ../sqlite-android-bindings.fossil | git fast-import
```
