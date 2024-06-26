
一个类库包，用于解析命令行风格参数

## 文件大小

file | size | gzip | brotli
:---- | :---- | :---- | :----
dist/main.cjs | 3.54kb | 1.26kb | 1.09kb
dist/main.js | 3.39kb | 1.19kb | 1.04kb
dist/main.min.cjs | 1.99kb | 0.96kb | 0.85kb
dist/main.min.js | 1.85kb | 0.90kb | 0.80kb
dist/main.umd.cjs | 4.09kb | 1.40kb | 1.22kb
dist/main.umd.min.cjs | 2.02kb | 1.00kb | 0.89kb


## 项目背景

为什么会用这样的一个类库包？它有什么价值吗？

在开发编码过程中，常常会编写一些命令工具辅助开发，曾有过在一定的短时期内，写了好几个工具，架构相似，只是业务逻辑不同，为了更好的复用，需要把公共部分提取出来。

曾有过这样的一个需求，后端已开发一个接口，需要前端直接复用后端的接口。

将价值简单粗暴地与金钱划上等号，我不知是对是错，但丢了根基，一切都不过是空中楼阁罢了。

人们常说的机遇是什么？我认为它就是：一个人在积累知识，学习技能的同时，善于用发展的眼光去观察这个快速变化的世界，当你有能力去解决某个问题时，它对你来说就是一次机遇。

## 当前功能

- 解析命令行风格参数
- 支持文本输入和JS 数组输入

## 用户安装

- 您可以通过npm cdn 直接引入
```html
<!-- unpkg.com/:package@:version/:file -->
<script src="https://unpkg.com/nano-argv-parse@1.0.0/dist/main.js"></script>

<!-- jsdelivr -->
<script src="https://cdn.jsdelivr.net/npm/nano-argv-parse@1.0.0/dist/main.js"></script>

<!-- unpkg.zhimg.com -->
```

- 您可以通过类库安装工具安装
```bash
npm i nano-argv-parse
```

```bash
yarn add nano-argv-parse
```

```bash
pnpm add nano-argv-parse
```

```ts
import {nanoargs} from 'nano-argv-parse'
console.log(nanoargs(`ns cmd -a -b -c -- -a -b -c`))
// {
//   flags: { a: true, b: true, c: true },
//   argv: [ 'ns', 'cmd' ],
//   extras: [ '-a', '-b', '-c' ]
// }
```

## 产品闭环

很小，功能单一，只做一件事——解析命令行风格参数

## 产品运维

因为功能简单，决定了它的开发速度，更新速度，问题速度不会很慢

## 产品计划

因为功能单一，功能已经基本完成，后期主要根据命令包或其他类库包的需要，更新小补丁，不会有功能大改的情况出现，架构可能会随着技术的更新而有变化

后面将开源一个使用此类库包的一个 在命令行界面编辑json文件的命令工具

## 许可证书

您可以使用它做任何事，但是请不要违发您所在地区法律。我不会为您的行为承担任何责任。

## 结束语

> 身为一名程序员我很自豪，虽然足不出户，指尖却有着可以改变世界 (可能有点大了) 自己的力量。即使不能实现，将其作为努力的目标也不错。———— 摘自 lencx

它就是一张白纸，您有什么设想，可以直接编码出来，怎么编，规则怎么定，有您决定。

