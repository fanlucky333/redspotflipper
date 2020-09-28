# redspotflipper
1，build
```
yarn build
```
2，test
```
yarn test
```
3，migrate
```
yarn migrate
```

在执行yarn test时，报超时的错如下：
```
Timeout - Async callback was not invoked within the 40000 ms timeout specified by jest.setTimeout.Error: Timeout - Async callback was not invoked within the 40000 ms timeout specified by jest.setTimeout.
```
这种情况一般是不是延迟超时时间就可以解决了？
