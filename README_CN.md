面向实体契约的程序设计语言-Solidity
你可以在Gitter和Matrix上与我们交流，在Twitter上推特我们，或者在Solidity论坛上创建一个新主题。欢迎提出问题、反馈和建议！
Solidity是一种静态类型、面向合同的高级语言，用于在以太坊平台上实现智能合同。
要获得良好的概述和起点，请访问官方的Solidity Language Portal。
正文目录
背景
搭建和安装
示例
参考文档
参与开发
开发维护
许可
安全声明

背景
Solidity是一种静态类型的花括号编程语言，用于开发在以太坊虚拟机上运行的智能合约。
智能合约是在对等网络内执行的程序，在对等网络中，没有人对执行具有特殊权限，因此，智能合约允许任何人实现价值标记、所有权、投票和其他类型的逻辑。
当部署智能合约时，应使用最新发布的Solidity版本。这是因为经常会引入突破性的更新、新功能和错误修复。我们目前使用0.x版本号来表示这种版本变化。

搭建和安装
关于如何构建和安装Solidity编译器的说明可以在Solidity文档中找到。

示例
与其他语言相比，Solidity中的“Hello World”程序的使用更少，但仍然：
// SPDX-License-Identifier: MIT
pragma solidity >=0.6.0 <0.9.0;

contract HelloWorld {
    function helloWorld() external pure returns (string memory) {
        return "Hello, World!";
    }
}

要开始使用Solidity，可以使用Remix，这是一个基于浏览器的IDE。以下是一些合同示例：
Voting（投票）
Blind Auction（拍卖）
Safe remote purchase（安全的远程支付）
Micropayment Channel（小额支付）

参考文档
Solidity的参考文档请查看这个文档。

参与开发
Solidity仍在发展中。随时欢迎贡献代码！如果您想提供帮助，请遵循《开发人员指南》。
您可以在项目部分找到我们当前的特性和即将发布的bug优先级。

开发者
@axic
@chriseth

许可
Solidity遵循GNU General Public License v3.0.
一些三方代码有自己的许可条例。

安全声明
安全声明见 这个文档。
