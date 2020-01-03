# 1-1 基本框架
```
#include <stdio.h>
#include <stdlib.h>

int main(void){ 

    return 0 ; //程式結束 回傳 0	
    
}
```

# 1-2 輸入文字
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    printf("Hello World!\n");  //利用 printf()輸出一串文字 
	
    system("pause");           //停留畫面
    return 0 ;                 //程式結束 回傳 0
    
}
```  
### 執行結果
```
Hello World!
```

# 1-3 運算結果
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int x = 123 ;          //宣告 x 值 = 123 
	
    int y = 2 * x + 99 ;   //宣告 y 值 = 2x + 99 
	
    printf("答案 = %d\n",y);  //輸出運算結果 
	
    system("pause");       //停留畫面 
    return 0;              //程式結束 回傳 0
    
}
```
### 執行結果
```
答案 = 345
```

# 1-4 大數 與 小數
```
#include <stdio.h>
#include <stdlib.h>

int main(void){

    int sum , difference ;           //宣告 sum 為兩數和 , difference 為兩數差 
    int bignumber , smallnumber ;    //宣告 分別存放 大數 與 小數

    sum = 10 ;          //指定數值 10 給變數 sum 
    difference = 4 ;    //指定數值 4 給變數 difference 

    bignumber = (sum + difference)/ 2 ;     //大數 = (和 + 差)/2 
    smallnumber = (sum - difference)/ 2 ;   //小數 = (和 - 差)/2
	
    printf("大數： %d\n",bignumber);    //輸出 大數的數值 
    printf("小數： %d\n",smallnumber);  //輸出 小數的數值 
	
    system("pause");   //停留畫面 
    return 0 ;         //程式結束 回傳 0 
    
}
```
### 執行結果
```
大數： 7
小數： 3
```

# 1-5 練習題 計算出(100+200+300)的值
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int a = 100 ; //宣告 a 值 = 100 
    int b = 200 ; //宣告 b 值 = 200 
    int c = 300 ; //宣告 c 值 = 300 
	
    printf("答案 = %d\n",a+b+c); //輸出100+200+300的結果 

    system("pause");  //停留畫面 
    return 0 ;        //程式結束 回傳 0 
    
} 
```
### 執行結果
```
答案 = 600 
```









