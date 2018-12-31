# Dapp
1.部署环境
安装并检查node与npm版本，我的版本如下：

安装truffle：
$ npm install -g truffle

2.启动插件
启动ganache，实现区块和账户可视化界面，其自动创建了10个账户，方便测试


在ganache的设置中，设置port，network id，这里使用的是8545端口，network id是5779


在Chrome浏览器上下载插件MateMask，点击下图中的红框区域

会出现如下界面，将Ganache的MNEMONIC（红框区域），复制到Wallet Seed，进行同步


点击如图红框处进行设置，在network处进行如下面右图所示的设置（根据Ganache的设置）


3.truffle框架的编译与部署
编译执行命令：truffle.cmd compile

部署执行命令：truffle.cmd migrate

此时产生6个区块，并消耗一定gas


4.开启服务器
执行命令：npm run dev


5.打开Dapp
输入http://localhost:3000/?#，进入页面
