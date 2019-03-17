---
layout: post
title: '腾讯暑期实习在线笔试题--魔法序列'
subtitle: '我好菜啊'
date: 2019-03-17
author: 伪君子
categories:
cover: ''
tags: Java 题解 腾讯
---

* content
{:toc}


## 0 前言
前段时间投实习，腾讯的暑期实习进了在线笔试。结果只做出了一道题（1/5），非常丢人。

没办法，只好把没做出的题目好好研究一下了。

## 1 题目--魔法序列
小 Q 拥有一个只存储了整数的序列叫魔法序列。一开始序列为空，小 Q 会执行以下两种操作：

add(x): 表示往序列中添加一个值为x的整数

get(y): 表示在第 y 次 add 操作后，取出序列中第 k 小的数，并将其输出，其中 k 初始时候为 1，每执行一次 get 操作之后，k 的值会 +1.

输入描述：
>第一行两个整数 n 和 m（0<=n，m<=30000，分别表示 add 和 get 的操作次数

>第二行 n 个空格间隔的整数，表示每次 add 操作往数列中添加的数字

>第三行m个空格间隔的整数 Yi(1<=Yi<=n) 其中第 i 个数表示在执行了 Yi 次 add 操作后，执行一次 get 操作.

输出描述：
>m 行，每行一个整数，表示对应 get 操作输出的值

输入：
>7 4
>3 1 -4 2 8 -1000 2
>1 2 6 6

输出：
>3
>3
>1
>2

## 2 Java 代码
先是导入需要的库，然后获取需要的值。

根据第三行的数来创建数组，创建好之后一一赋值到新数组，然后排序，输出对应的值，然后 k 自增。
```Java
import java.util.Scanner;
import static java.util.Arrays.sort;  //用来排序

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();  //获取整数 n
        int m = sc.nextInt();  //获取整数 m
        int[] add = new int[n];  //定义第二行的数组
        int[] b = new int[m];  //定义第三行的数组
        int k = 1;

        for (int i = 0; i < n; i++) {
            add[i] = sc.nextInt();  //获取第二行的数
        }
        for (int j = 0; j < m; j++) {
            b[j] = sc.nextInt();  //获取第三行的数
        }

    	for(int j = 0; j < b.length; j++) {
            int[] newArray = new int[b[j]];  //根据 b[j] 的值来确定新数组的长度
            for (int x=0;x<newArray.length;x++){
                newArray[x] = add[x];  //根据新数组的长度把第二行的数一一赋给 newArray
            }
    			sort(newArray);  //从小到大排序
    			System.out.println(newArray[(k-1)]);  //输出对应的值
    			k+=1;  //get 操作完成，k+1
    	}
    }
}
```
我是考完之后让大佬检查我的代码，所以代码不一定能够完全通过所有的测试样例，但是我觉得都可以通过🤣