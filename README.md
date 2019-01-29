# HOC概念:
## 1.高阶组件就是接受一个组件作为参数并返回一个新组件的函数
## 2.高阶组件是一个函数，并不是一个组件 
* 示例：
    >react-redux中的connect  
* 如何编写：
    >首先，实现一个普通组件；然后，将普通组件使用函数包裹起来   
    >1.higherOrderComponent(WrappedComponent)  
    >2.@higherOrderComponent  
    >![image](https://github.com/lmmProject/react_02_hoc/blob/master/eject.png)  
# 高阶组件的应用（优先代理）：  
## 代理：1、操作prop; 2、抽取状态； 3、访问ref(慎用)；4、包装组件  
## 继承：1、操作prop; 2、操纵生命周期函数  
![image](https://github.com/lmmProject/react_02_hoc/blob/master/proxy%26extends.png)