# Markdown学习
所有内容参考：[Markdown](https://www.runoob.com/markdown/md-tutorial.html)
 
# 第一标题
## 第二标题
### 第三标题
#### 第四标题
 ##之后就是标题

>这是一次引用
/* > 之后是引用 */

有序列表：
 1. 吃早饭
 2. 睡觉
 3. 吃晚饭

无序列表：
- 绝地学徒
- 寰宇守护
* 大洋超人
* 海洋游侠

任务列表：
- [ ] 过早
- [x] 过午
- [x] 过晚

代码块： 
```c
int main(){
return 0;
}
```
数学公式：与Latex用法相同
$$
 \frac{abc123}{xyz123}
$$

表格:
|姓名|年龄|成绩|
|:---|---:|:---:|      
|张三|19|99|                //冒号左边是左对齐，冒号在右边是右对齐，冒号在中间时居中对齐
|李四|19|98|                

横线：

---

链接：
这是一个链接[Markdown教程](https://www.runoob.com/markdown/md-tutorial.html)

[emoji链接](https://unicode.org/emoji/charts/full-emoji-list.html "emoji的unicode")

[bilibili](https://www.bilibili.com/)

[bilibili][website1],[bilibili][website1],[bilibili][website1]  

[website1]: bilibili.com              "这个链接用website1作为网址变量,在后面为变量赋值(网址)"

请参考[第一标题](#第一标题)

图片：

![百度][def]

[def]: www.baidu.com

