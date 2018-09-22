workspace
=========

Learning stage

知识点梳理


export&import

export let client = 'APP'  //输出变量
export function mul(x, y){  //输出函数
    return x + y
}
export class Toast(){} //输出类



Restful API 
REST 全称 Representation State Transfor (资源表现层状态改变)

实际上是指客户端通过http/https协议手段来改变URI的状态转化，达到请求不同的资源的目的。

包括 ： 1 每个URI代表一种资源

 　　　 2 客户端和服务器之间，传递这种资源的数据和状态的转化

       3 客户端通过http 的请求方式来对服务器资源进行操作，实现表现层的状态转化

RESTful API 定义接口的处理方式；通过对http 路径的定义以及状态码来达到请求资源的目的。
