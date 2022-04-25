## 密码学库
业务系统可以直接引用密码学库（当前仅支持Go语言、JS未开源）进行账户创建、生成签名等操作，关于纵向联邦学习算法详解，参考 [Crypto](https://github.com/PaddlePaddle/PaddleDTX/tree/master/crypto)。

### 账户生成
``` go linenums="1"
import (
    "github.com/PaddlePaddle/PaddleDTX/crypto/core/ecdsa"
)
prikey, pubkey, err := ecdsa.GenerateKeyPair()
```


### 签名生成
计算节点与区块链网络、任务执行节点交互，数据持有节点客户端上传下载文件等，部分操作均需要生成签名，签名生成规则如下：
``` go linenums="1"
import (
    "github.com/PaddlePaddle/PaddleDTX/crypto/core/ecdsa"
	"github.com/PaddlePaddle/PaddleDTX/crypto/core/hash"
)
// mes待签名信息
sig, err := ecdsa.Sign(privkey, hash.HashUsingSha256(mes))
```


<br>










