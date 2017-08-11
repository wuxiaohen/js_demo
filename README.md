## 存放一些js的demo，最新特性，或者比较有趣的写法，或者经典，不定期更新

`lyb` *热爱生活热爱人生*

 1. 回调函数的各种写法

 2. 实现数组去重的一个巧妙的思路

  ```
  const exists = {};
  [1,2,3,1,'a',1,'a'].filter(item => {
    if (exists[item]) return false
    exists[item] = true
    return true
  })>
  ```