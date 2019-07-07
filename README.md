To test things locally, run the following after cloning:
```
$ git clone --recursive https://github.com/gohugoio/hugoThemes themes/
```

To add a new article with auto-generated timestamp (will be marked as a draft by default):
```
$ hugo new posts/a-new-post-title.md
```

Run this to build the result and output to the `public/` folder.
```
$ hugo
```

**Please Note**: The server checks this git repository for changes every 15 minutes. Test locally, *then* publish.
```
$ hugo server -D
```
