# vuex-analysis
vuex 源码解析

## 前言

我一直想完整地阅读一个库的源码，而不仅仅是停留在 API 调用的层面上，但无奈没有坚持下来。摸过 jQuery，尝过 underscore，但都半途而废了，真是郁闷至极。反思了再反思，一方面是自己的基础还不够扎实，另一方面是有点大跃进（一下子拿那么大的库来研究，还真有点坚持不下来）。

说了这么多，只能说自己还是太水了。我把目标转向了 vuex，它的代码相比来说少很多，API 不多，日常经常使用到，会比较熟悉。

这次我不打算逐行研究代码，这只会给我带来负担与焦虑。我打算从一个大体的方向去了解整个库，所以只会有核心代码的解析。虽然这样可能会有点浅尝辄止，但我相信只要了解了整体结构，接下来具体的细节代码以后想深入研究也不迟。

预备......

## 文章

1. [vuex 安装原理](https://github.com/cobish/vuex-analysis/issues/1)

## 计划

计划主要是对 vuex 的 state、getter、mutation、action 和 module 做一个深入的了解，对插件与热重载暂时忽略。

- [x] vuex 安装原理。
- [ ] State 实现原理。
- [ ] mapState 实现原理。
- [ ] Getter 实现原理。
- [ ] mapGetter 实现原理。
- [ ] Mutation 实现原理。
- [ ] mapMutation 实现原理。
- [ ] Action 实现原理。
- [ ] mapAction 实现原理。
- [ ] Module 实现原理。

## License

MIT

