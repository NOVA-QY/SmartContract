# SmartContract
用Solidity编写智能合约，实现员工薪酬系统  

## （一）Solidity智能合约示例
**声明程序版本**
```solidity
pragma solidity ^0.4.0
```
**合约声明**
```solidity
contract SimpleStorage{
}
```

**状态变量**
```solidity
contract SimpleStorage{
    uint storedData;
}
```

**合约方法**
```solidity
contract SimpleStorage{
    uint storedData;
    
    function set(uint x){
        storedData=x;
    }
    
    function get() constant returns (uint){
        return stroedData;
    }
}
```
注：constant在此无效

## 在线IDE  
remix.ethereum.org
