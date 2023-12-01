## 学习Markdown格式

1. 标题
   # 我是标题h1
   ## 我是标题h2
   ### 我是标题h3
   #### 我是标题h4 
   ##### 我是标题h5
   ###### 我是标题h6 

2. 链接（a标签）  
   [标签文本内容](http://www.baidu.com "title可选")

3. 图片（image标签）  
   1. 网络图片  
      ![图片加载失败时显示的文本描述信息](https://tse4-mm.cn.bing.net/th/id/OIP-C.duz6S7Fvygrqd6Yj_DcXAQHaF7?rs=1&pid=ImgDetMain,"title可选")
   2. 本地图片：  
      ![图片加载失败时显示的文本描述信息](/images/1.jpg,"title可选")

4. 字体效果  
   1.斜体（em标签）  
     *斜体*  
   2.粗体（strong标签）  
     **粗体**

5. 有序列表  
   1. item1  
   2. item2  
   3. item3  
   4. item4  
   5. item5  

6. 无序列表
   * item1  
   * item2  
   * item3  
   * item4  
   * item5  

7. 手动换行，在末尾输入2个或以上空格  
   您好，  
   大家好。
8. 代码
   1. 单行代码  
      `#include<stdio.h>`   
   2. 代码块  
      ```
      #include<stdio.h>   
      #include<stdlib.h>
      ```
9. 代码格式化，代码前面空4个空格或者一个tab键   

        #include <stdio.h>
        typedef unsigned char byte;
        int main(int argc, char const *argv[])  
        {  
          byte b = 200;  
          printf("b=%u\n", b);  
          return 0;  
         }           

10. 引用
   > 引用的内容，可以是任何内容，纯文字、代码、图片等等


11. 转义(已经提供这些字符的转义显示)
    ###显示`字符本身：
    You can include literal backticks
    like `` `this` ``.
    ###显示斜杠
    \

12. 分割线（hr标签），可以用3个*、3个-、4个-，如下

   * * * 
   ---
   - - - -
