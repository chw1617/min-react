# min-react
手写min-react的原理实现
# 前端主流框架vue、react 有很多相似的地方，主要分为两个大块：编译时 + 运行时
vue 
1、编译时,自己实现了一个vue@complier-sfc 单文件编译是将模板编译成 render 函数，
2、运行时 是通过 render 函数生成 vdom，最后通过 vnode 生成真实 dom
react
1、编译时借助babel将 jsx 编译成 vdom
2、react  运行时 然后通过 vdom 生成 fiber，最后通过 fiber 生成真实 dom

# 目前实现的功能如下
  1、jsx --> vdom
  2、vdom --> dom
  3、vdom --> fiber --> dom
