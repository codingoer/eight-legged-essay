# interview-guide

## Install docsify

全局安装

```bash
npm i docsify-cli -g
```

输出：

```
/Users/lionel/.nvm/versions/node/v14.15.0/bin/docsify -> /Users/lionel/.nvm/versions/node/v14.15.0/lib/node_modules/docsify-cli/bin/docsify

> docsify@4.12.2 postinstall /Users/lionel/.nvm/versions/node/v14.15.0/lib/node_modules/docsify-cli/node_modules/docsify
> opencollective-postinstall

Thank you for using docsify!
If you rely on this package, please consider supporting our open collective:
> https://opencollective.com/docsify/donate

+ docsify-cli@4.4.3
added 214 packages from 97 contributors in 9.398s
```

根据提示进入安装目录
```bash
cd /Users/lionel/.nvm/versions/node/v14.15.0/bin/
ls -l
```

```bash
total 144600
lrwxr-xr-x  1 lionel  staff        43  2 28 23:40 docsify -> ../lib/node_modules/docsify-cli/bin/docsify
-rwxr-xr-x  1 lionel  staff  74032864 10 27  2020 node
lrwxr-xr-x  1 lionel  staff        38 10 27  2020 npm -> ../lib/node_modules/npm/bin/npm-cli.js
lrwxr-xr-x  1 lionel  staff        38 10 27  2020 npx -> ../lib/node_modules/npm/bin/npx-cli.js
```

可以看到是一个软连接，也就是安装目录在
`/Users/lionel/.nvm/versions/node/v14.15.0/lib/node_modules/docsify-cli/bin/docsify`