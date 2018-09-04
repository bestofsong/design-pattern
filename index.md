## 抽象工厂
```
实用
```

- 适用条件
  - 有一个类比于工厂的类用于创建一个或多个产品
  - 这个工厂是抽象的，可以有不同的具体类，生产具有不同视感（look and feel）产品
- 效果
  - 便于整体替换全部产品（抽象的工厂，和产品）
  - 更少的if判断（if判断提升到创建具体工厂的地方）

- Show me the code
  -  http://code.smartstudy.com/mobileapp/zhike-mobile/blob/master/src/model/course.js#L234
  - http://code.smartstudy.com/mobileapp/zhike-mobile/blob/master/src/components/study_center/index.js#L169
  - http://code.smartstudy.com/mobileapp/zhike-mobile/blob/master/src/components/course_item/index.js#L121
  - http://code.smartstudy.com/mobileapp/zhike-mobile/blob/master/src/components/study_center/index.js#L74
## 组合模式( Composite Pattern )

```
常见，但是容易被忽略
```

- 适用条件
  - 树形结构
  - 组合对象可以向单个对象一样使用
- 实现细节
  - 是否在公共基类提供管理子节点的接口
    - 更透明
    - 更安全

## React 
- 受控组件、非受控组件(https://github.com/SangKa/react-in-patterns-cn/blob/master/book/chapter-5/README.md)
- 高阶组件(https://github.com/SangKa/react-in-patterns-cn/blob/master/book/chapter-4/README.md#%E9%AB%98%E9%98%B6%E7%BB%84%E4%BB%B6)