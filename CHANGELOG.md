## 1.1.5

新增公共方法getVM(),得到ViewModel全局调用的语法糖。

initMVVM 初始化新增参数 DataFromNetworkOrDatabase ，

数据来源  网络或者数据库 [true] : 网络 --- [false] ：数据库

场景：网络无连接 页面数据缓存在数据库  切换数据来源，改从数据库取数据

## 1.1.4
BaseView新增获取对应ViewModel方法 VM vm(BuildContext context)；

BaseViewOfState新增获取对应ViewModel方法 VM vm()；

## 1.1.3
优化根布局刷新，修复当开启根布局不刷新后，页面为空或者数据错误，点击刷新没有效果。
增加demo状态页配置案例。

## 1.1.2
修复单独页面配置状态页类型错误。

## 1.1.1
修复不规范配置 上拉刷新下拉加载 造成的空异常。

## 1.1.0
优化刷新的空判断。

## 1.0.9

去掉 flutter_easyrefresh 依赖，initMVVM增加上拉刷新下拉加载全局配置

## 1.0.8
优化的刷新控制，子类可以自己实现控制

BaseListViewModel

BaseListViewModel({params, refreshController})
      : super(defaultOfParams: params) {
    _refreshController = refreshController;
  }

resetRefreshState｜finishRefresh｜resetLoadState｜finishLoad

## 1.0.7
优化代码和注释。

## 1.0.6
修复开启根布局不刷新，下拉刷新获取数据状态控制失效
新增下拉刷新方法 pullRefresh()

## 1.0.5
Demo 增加关于数据刷新的展示。

## 1.0.4
修复http跟本地组装数据

## 1.0.3
initMVVM 初始化提供全局状态页配置

## 1.0.2
更正说明

## 1.0.1
更新一下说明 和案例

## 0.0.1
首次上传 有简单的demo 暂时处理的不完善
