# api
## getIp
```javascript
'use strict';

var q = require('qiao-get-ip');

var test = async function(){
    try{
        var ip = await q.getIp();
        console.log(ip);
    }catch(e){
        console.log(e);
    }
};

test();
```

# version
## 0.0.1.20200819
1. init project
2. http method
3. qiao-get-ip
4. get ip by sohu
5. get ip by icanhazip
6. get ip