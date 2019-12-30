title: learn_alg
tags: alg
categories: alg

Algorithm



工具

- 在腾讯云平台
- 用git仓库管理



基础语法

    #include<iostream>
    using namespace std;
    int main()
    {
        int a;
        cout << "a:";
        cin >> a;
        cout << "a=" << a << endl;
        cout << "Hello" << endl;
        return 0;
    }
    
    /*
    编辑 ：  vi    gedit
    编译(目标文件）: gcc   g++    g++ -0 hello hello.cpp
    链接（可执行文件）:  ./hello.out
    测试
    */
    
    int a;
    unsigned int a;  //无符号整数
    const int a=10;  //常量，不能变
    double a，b;
    
    
    
    





基础算法



打印

    #include<stdio.h>
    int main()
    {
        printf("hello \n");   //  \转义字符
        return 0;
    }
    
    
    
    //循环实现
    void printN(int n)
    {
        int i;
        for(i=1;i<n;i++)
        {
            printf("%d \n",i); 
        }
        return ;
    }
    
    //递归实现
    void printN(int n)
    {
        if(n)
        {
            printN(n-1);
            printf("%d\n", n);
        }
        return ;
    }
    




