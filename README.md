# WYSwiftyMediator

[![CI Status](https://img.shields.io/travis/wy/WYSwiftyMediator.svg?style=flat)](https://travis-ci.org/wy/WYSwiftyMediator)
[![Version](https://img.shields.io/cocoapods/v/WYSwiftyMediator.svg?style=flat)](https://cocoapods.org/pods/WYSwiftyMediator)
[![License](https://img.shields.io/cocoapods/l/WYSwiftyMediator.svg?style=flat)](https://cocoapods.org/pods/WYSwiftyMediator)
[![Platform](https://img.shields.io/cocoapods/p/WYSwiftyMediator.svg?style=flat)](https://cocoapods.org/pods/WYSwiftyMediator)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

WYSwiftyMediator is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'WYSwiftyMediator'
```

## Author

wy, wangyu@shanda.com

## License

WYSwiftyMediator is available under the MIT license. See the LICENSE file for more info.

如果无法找到此库，请按照以下方式更新本地cocoapods
cd ~/.cocoapods
ls
cd repos
ls
cd cocoapods
ls
ls -a
git pull
//简单的介绍一下该方法第一行cd ~/.cocoapods是进入到本地的cocoapods类库根目录 ls是显示该目录下有哪些文件之后一直cd 下去到了cocoapods文件夹
//cocoapods中的Specs文件夹就是存放者本地的第三方库的目录,每个文件夹里有一个json文件介绍了该三方的基本情况(版本,适用iOS版本等等)
//ls -a是显示该文件夹下的隐藏文件,会发现有一个.git文件说明该文件夹是一个git厂库,说以可以使用git的方法更新该文件夹的内容 
//git pull等待执行完毕即可
