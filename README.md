# vuex-analysis

vuex 2.0 源码解读

## 前言

我一直想完整地阅读一个库的源码，而不仅仅是停留在 API 调用的层面上，但无奈没有坚持下来。摸过 jQuery，尝过 underscore，但都半途而废了，真是郁闷至极。反思了再反思，一方面是自己的基础还不够扎实，另一方面是有点大跃进（一下子拿那么大的库来研究，还真有点坚持不下来）。

说了这么多，只能说自己还是太水了。我把目标转向了 vuex 2.0，它的代码相比来说少很多，API 不多，工作中也常用到，比较熟悉。

本次解读不打算逐行研究代码，而是打算从一个大体的方向去了解整个库，所以只会有核心代码的解析。虽然这样可能会有点浅尝辄止，但我相信只要了解了整体结构，接下来具体的细节代码以后想深入研究也不迟。

预备......

## 文章

1. [vuex 解读之 install](https://github.com/cobish/vuex-analysis/issues/1)
2. [vuex 解读之 state](https://github.com/cobish/vuex-analysis/issues/2)
3. [vuex 解读之 mapState](https://github.com/cobish/vuex-analysis/issues/4)
4. [vuex 解读之 getter](https://github.com/cobish/vuex-analysis/issues/5)
5. [vuex 解读之 mapGetters](https://github.com/cobish/vuex-analysis/issues/6)
6. [vuex 解读之 mutation](https://github.com/cobish/vuex-analysis/issues/7)
7. [vuex 解读之 mapMutations](https://github.com/cobish/vuex-analysis/issues/8)
8. [vuex 解读之 action](https://github.com/cobish/vuex-analysis/issues/9)
9. [vuex 解读之 mapActions](https://github.com/cobish/vuex-analysis/issues/10)
10. [vuex 解读之 module](https://github.com/cobish/vuex-analysis/issues/11)

## 计划

计划主要是对 vuex 的 state、getter、mutation、action 和 module 做一个深入的了解，对插件与热重载暂时忽略。

- [x] vuex 安装原理。
- [x] state 实现原理。
- [x] mapState 实现原理。
- [x] getter 实现原理。
- [x] mapGetters 实现原理。
- [x] mutation 实现原理。
- [x] mapMutations 实现原理。
- [x] action 实现原理。
- [x] mapActions 实现原理。
- [x] module 实现原理。

## 版本

下载 [vuex 2.0.0](https://github.com/vuejs/vuex/tree/v2.0.0) 源码，结合文章对 vuex 进行一个深入的了解。

## License

MIT

