# @jiaminghi data-view for vite2 vue3 cnpm/npm/pnpm/yarn windows/macos大补丁

#### 介绍
@jiaminghi data-view for vite2 vue3 cnpm/npm/pnpm/yarn windows/macos大补丁

#### 使用说明

npm版本/yarn版本通用
资源下载地址：https://download.csdn.net/download/hehu158/85008259

cnpm版本
资源下载地址：https://download.csdn.net/download/hehu158/81842518

pnpm版本
资源下载地址：https://download.csdn.net/download/hehu158/85005243


官网直接安装的不支持vite2+vue3的

主要修复：

1.build或者dev项目时不报错，兼容vite2，vue3；

2.加入deep监听watch，直接在父组件中修改图表中的config参数即可完成图表中的数据变更。


yarn npm cnpm pnpm可通用的，就是底层node_modules位置不一样而已，不过修改原理都是一样的，大家可以自行下载研究，目前仅在windows、macos下测试，linux还未测试。


下面说下安装步骤：

1.在项目更目录中安装，执行cnpm install @jiaminghi/data-view即可；

2.将other_modules压缩包解压并覆盖到项目的node_modules文件夹下即可

调用方法，请参考官网文档http://datav.jiaminghi.com/

修复报错：

默认新装报错1

[plugin:vite:vue]

/node_modules/@jiaminghi/data-view/lib/components/decoration6/src/main.vue:8:11

6  |        >

7  |         <rect

8  |            :key="i"

   |             ^

9  |            :fill="mergedColor[Math.random() > 0.5 ? 0 : 1]"

10 |            :x="point[0] - halfRectWidth"



默认报错2:

The requested module '/node_modules/@jiaminghi/c-render/lib/index.js?v=66938fb6' does not provide an export named 'default
