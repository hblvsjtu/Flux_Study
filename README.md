# React_Study

## 六、Flux架构及其实现

### 作者：冰红茶  
### 参考书籍：《React全栈》 张轩 杨寒星  &&   《深入React技术栈》 陈屹 
### 参考源：[Flux 官网](http://facebook.github.io/flux/docs/in-depth-overview.html#content) 
### 参考源：[Flux Example](https://github.com/facebook/flux/tree/master/examples)
### 参考源：[REACT ROUTER教学视频](https://www.bilibili.com/video/av22934284/?p=21)
### [源码](https://github.com/hblvsjtu/React_Study/tree/master/React/practice/app/todolist)
------    



   面对多向复杂交错的数据流动的时候，明显发现MVC架构对此无能为力，但是如果数据是单向的话呢，由于每个view对应一个model，View的重渲染很容易会使得性能受到严重影响。而Flux特有的单项数据流架构，与React的合作，恰好能解决这个单项数据流动造成的渲染性能的问题。但是对于原本使用MVC就能解决的问题，使用Flux明显有点用牛刀杀鸡了^_ ^
     
  
## 目录

### [六、Flux架构及其实现](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现)
### [6.1 简介](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.1)
#### [6.1.1 背景和特点](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.1.1)
#### [6.1.2 control-view](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.1.2)
### [6.2 项目 todolist](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.2)
#### [6.2.1 准备工作](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.2.1)
#### [6.2.2 相关依赖解释](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.2.2)
#### [6.2.3 相关文件](https://github.com/hblvsjtu/React_Study/blob/master/六、Flux架构及其实现#6.2.3)

