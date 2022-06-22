使用说明可详见（有图说明）：https://blog.csdn.net/ling1998/article/details/124919822?spm=1001.2014.3001.5501

# 访问网址
访问如下网址（github服务），可在线预览效果及功能体验  
https://tracyzhang1998.github.io/demo.html

# 验证Web3功能
## 设置MetaMata连接站点链接

未连接MetaMask，虽然显示成功，但是账户信息没有加载，当然所有功能也用不了，所以先设置一下，这点也需要再完善下（当链接还没连接MetaMask时给个提示信息，引导用户操作），完善后再补充该文章。目前先提前操作一下：

步骤如下：
1. 点击浏览器导航中的MetaMask插件，选择Ropsten Test Network，点击账户右侧三个点，选择"Connected sites"
2. 点击下方链接“Manually connect to current site”
3. 选择要连接网址的账户，点击“Next” button
4. 点击“Connect” button，此时看到状态已变成Connected

再次刷新页面，已加载账户信息

## 验证账户信息
输入另外一个账户地址，点击“查询余额”，能够看到账户余额已变更，且与实际账户余额相等，验证成功

## 验证转账（交易）
输入转账金额，点击“转账”按钮，弹出MetaMask，点击“Confirm”，交易生成后，交易Hash将显示出来

交易等待上链，生成新区块后，查看余额，转入账户余额已增加，转出账户余额减少，验证成功

## 验证合约调用
### 调用合约函数 - 设置消息
在设置消息前，先看下查询消息文本框中显示的内容，再在设置消息文本框输入一个新的消息（如“Good morning!”），点击“设置消息”按钮，弹出MetaMask，点击“Confirm”，交易生成后，交易Hash将显示出来

### 调用合约函数 - 查询消息
交易等待上链，生成新区块后，点击“查看消息”，此时消息变更为“Good morning!”，验证成功！！！
