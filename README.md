# jiaminghi-data-view-datav-for-vite2-vue3

# @jiaminghi data-view for vite2 vue3 pnpm windows大补丁

#### 介绍
@jiaminghi data-view for vite2 vue3 pnpm windows大补丁

#### 使用说明

资源下载地址：https://download.csdn.net/download/hehu158/81842518

官网直接安装的不支持vite2+vue3的

主要修复：

1.build或者dev项目时不报错，兼容vite2，vue3；

2.加入deep监听watch，直接在父组件中修改图表中的config参数即可完成图表中的数据变更。


yard npm cnpm pnpm各不通用的，不过修改原理都是一样的，大家可以自行下载研究，目前仅在windows下测试，macos跟linux还未测试。


下面说下安装步骤：

1.在项目更目录中安装，执行cnpm install @jiaminghi/data-view即可；

2.将other_modules压缩包解压并覆盖到项目的node_modules文件夹下即可

