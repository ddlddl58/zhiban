# zhiban
一个自动生成值班excel的程序

先手工创建csv文件,
headers = [日期,输出结果,日期2,星期几,值班人员]  
在C列输入2019/1/1,然后下拉出现全年的日期，  
在A列生成20190101的日期格式=TEXT(C2,"yyyymmdd")，  
在D列生成星期几的格式=TEXT(C2,"aaaa")，  
调用脚本，在B列生成节假日信息。(工作日-0, 法定节假日-1,节假日调休补班-2，休息日-3)，在E列生成值班人员信息。  
