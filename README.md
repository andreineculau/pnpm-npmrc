``` shell
$ ./test
false < expected without ./.npmrc
false
true < expected with ./.npmrc
true
true < expected without ./.npmrc, but with ../.npmrc, no package.json
true
false < expected without .npmrc, with ../../.npmrc but with package.json
false
```
