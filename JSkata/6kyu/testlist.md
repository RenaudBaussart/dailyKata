## Function Composition [link](https://www.codewars.com/kata/5421c6a2dda52688f6000af8/train/javascript)

```TS
function compose(f,g) {
  // at first i have try
  // return (x) => (f(g(x)));
  // not working because it have 2 "locked" argument so i use rest parameters
  return (...args) => f(g(...args));
}
```
## 