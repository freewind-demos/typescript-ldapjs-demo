TypeScript Ldapjs Demo
=======================

Use ldapjs to query data from  <https://www.forumsys.com/tutorials/integration-how-to/ldap/online-ldap-test-server/> 

注意：ldapjs有个bug，`client.unbind`中的callback不会被调用。
所以如果对其进行封装成为async的话，`resolve/reject`不能放在callback里。

https://github.com/ldapjs/node-ldapjs/issues/483#issuecomment-410075856

推荐使用ldapts，代码更好，bug更少，自带typing

```
npm install
npm run demo
```

