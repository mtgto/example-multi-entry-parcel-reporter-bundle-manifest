# Pass entry files to arguments of parcel cli

```console
$ yarn run parcel a.js b.js

$ cat dist/parcel-manifest.json
{"a.js":"/a.js","b.js":"/b.js"}
```

```console
$ yarn run parcel build a.js b.js

$ cat dist/parcel-manifest.json
{"a.js":"/a.js","b.js":"/b.js"}
```
