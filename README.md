# cool things 
## __一起做有意义的事__
  “酷事”的业务是类比于把知乎的“问题”替换为“酷事”，用户匿名发布“酷事”，其他用户浏览酷事的时候可以选择践行这个酷事并发布晒出。
  
  
## __框架__
  本项目没有使用任何主流框架，而是使用composer集成、架构的一个个人轻型框架。框架完全放弃使用控制器渲染页面，静态化页面，前后端分离。后端使用api与前端交互。
  
  还是安利一下我的这个框架吧。
1. 本框架名称暂定与本项目同名，很酷。
2. MSC结构，model层、service层、contoller层，页面静态化的后端当然没有view层了，想啥呢。
3. laravel的路由是每个都需要定义，否则不能访问，我的也是^^。但是没有那么麻烦，直接在配置文件config——route.php里写数组就行
4. 具体使用规则在本项目初步结束，使用初步成熟的时候再写。

## __注意__
  本框架遵循极简的原则（其实是怕费事），所以我们只使用mysql！且！每个数据表的主键名只用"id"。如果强行使用其它名字也可以勉强，但是有时候会出抛错的哦，别怪我没有提醒==
