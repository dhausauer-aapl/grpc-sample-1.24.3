Reproduction:

```
$ nvm use 12.13.0
$ npm install
$ npm test

node(66630,0x107dfddc0) malloc: *** error for object 0x102c0ab60: pointer being freed was not allocated
node(66630,0x107dfddc0) malloc: *** set a breakpoint in malloc_error_break to debug
[1]    66629 abort      npm test
```
