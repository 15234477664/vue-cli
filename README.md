# 路由组件异步加载（模块过多时修改后启动慢）
方式一(不建议)：

![Image text](https://github.com/15234477664/vue-cli/blob/master/img/1.png)

这种情况下一个组件生成一个js文件，导致了加载的时候比较缓慢

方式二(官方推荐)：

![Image text](https://github.com/15234477664/vue-cli/blob/master/img/2.png)

注： webpackChunkName定以后，webpack打包时会将相同的打包到一个文件中，把组件按组分块

解决75%打包等待的问题
