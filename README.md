# 河南宗教自动答题 1.5
### 最近更新 2021-11-28      V1.5
更新内容：

       1、重写了答案匹配机制，答案匹配成功率高达95%   
       
       【题库是学校发的，部分答案对不上，有错误需要大家提交issues】 
       
       2、新增了windows可执行文件版本
       
### 注：如果报错【{success:0,msg:'非法操作，涉嫌刷题1'}】  自行查看自己的IP地址是不是河南范围，一定要是河南范围，不要挂梯子！！
       
       

#### 介绍
河南宗教自动答题,完成自动提交试题，经测试，得分均稳定在90以上，可以自行部署到云函数上，或者action，每天自动执行更省心，

#### 目录结构
-tool [工具目录]

    - dealData.py [文本处理]
    
    - driver.py [操作手]
    
    - fuzz.py [答案匹配]
    
-control.py [入口程序]



#### 使用说明
源码版本：
	编辑control.py，填入自己的信息，python control.py运行即可

exe版：
         双击运行


#### 题库项目 最近更新2021-11-28
 题库项目地址 https://github.com/aqz236/aqz236-hnzjtk
