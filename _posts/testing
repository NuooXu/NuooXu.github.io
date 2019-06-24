---
layout:     post   				    # 使用的布局（不需要改）
title:      Problem find 				# 标题 
subtitle:   what is the problem #副标题
date:       2019-06-24				# 时间
author:     Nuo Xu 						# 作者
header-img:              	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签
    - Leetcode刷题
---
# 学习内容
HW 0: A Java Crash Course

## 练习1
1.打印指定行数的三角形  

2.找到一列数组中的最大值

### 代码
```java
public class learning {
    public static void main(String[] args) {
        drawTriangle(10);
        int[] numbers = new int[]{9, 2, 15, 2, 22, 10, 6};
        System.out.println(max(numbers));
    }
    /**打印指定行数的三角形*/
    public static void drawTriangle(int N){
        for(int x = 1;x<N + 1;x++){
            for(int y = x;y>0;y--){
                System.out.print("*");
            }
            System.out.println();
        }
    }
    /** Returns the maximum value from m. */
    public static int max(int[] m) {
        int max = 0;
        int value = 0;
        if (m.length == 1){
            return m[0];
        }else{
            for(int i = 0;i<m.length-1;i++){
                int s = m[i] - m[i+1];
                if (s>0){
                    value = m[i];
                }else {
                    value = m[i+1];
                }
                int t = max - value;
                if (t>0){
                    max = max;
                }else {
                    max = value;
                }
            }
        }
        return max;
    }
}
```
