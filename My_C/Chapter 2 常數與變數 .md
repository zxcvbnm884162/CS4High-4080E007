# 定義常數
```
#define 常數名稱 常數值
```

# 2-1 計算圓周長
```
#include <stdio.h>
#include <stdlib.h>

#define R  5.0      //定義 半徑 
#define PI 3.14159  //定義 圓周率常數 

int main(void){
	
    printf("圓周長 = %f\n",2 * PI * R) ; //計算半徑為5.0的圓周長 
	
    system("pause"); //停留畫面 
    return 0;        //程式結束 回傳 0 
	
} 
```
### 執行結果
```
圓周長 = 31.415900
```

# 2-2 顯示手搖飲的售價
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int Signature_Milk_Tea = 40 ; //宣告 招牌奶茶的變數並指定初值 
    int Pearl_milk_tea = 45 ;     //宣告 珍珠奶茶的變數並指定初值 
	
    int cup_Signature_Milk_Tea = 1 ; //招牌奶茶的杯數初值為 1杯 
    int cup_Pearl_milk_tea = 1 ;     //珍珠奶茶的杯數初值為 1杯 
	
    printf("招牌奶茶 %d 杯 %d 元\n",cup_Signature_Milk_Tea,Signature_Milk_Tea);
    printf("珍珠奶茶 %d 杯 %d 元\n",cup_Pearl_milk_tea,Pearl_milk_tea);
	
    system("pause"); //停留畫面 
    return 0;        //程式結束 回傳 0 
} 
```
### 執行結果
```
招牌奶茶 1 杯 40 元
珍珠奶茶 1 杯 45 元
```

# 2-3 指定變數值
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int Cappuccino = 50 ;    //宣告卡布其諾的變數並指定初值 
    int cup_Cappuccino = 5 ; //宣告卡布其諾的杯數初值為 5杯 
    int total_price = 0 ;    //宣告結帳金額的變數並指定初值 
    
    printf("卡布其諾咖啡 原價一杯 %d 元\n",Cappuccino);
	
    total_price = Cappuccino * cup_Cappuccino ;
	
    printf("帳單：卡布其諾 %d 杯 %d 元\n",cup_Cappuccino,total_price);

	
    system("pause"); //停留畫面 
    return 0;        //程式結束 回傳 0 
} 
```
### 執行結果
```
卡布奇諾咖啡 原價一杯 50 元
帳單： 卡布奇諾 5 杯 250 元
```

# 2-4 兩個變數值交換
```
#include <stdio.h>
#include <stdlib.h>

int main(void){

    int a = 1000 ; //宣告變數a值 
    int b = 2000 ; //宣告變數b值 
    int temp = 0 ; //宣告暫存變數 

    printf("交換前： a = %d , b = %d\n",a,b);
	
    temp = a ; // a 傳給 temp   
    a  =  b ;  //b 傳給 a 
    b = temp ; //temp 傳給 b 
	
    printf("交換後： a = %d , b = %d\n",a,b);
  
    system("pause"); //停留畫面 
    return 0 ;       //程式結束 回傳 0 
	
}
```
### 執行結果
```
交換前： a = 1000 , b = 2000
交換後： a = 2000 , b = 1000
```
# 2-5 練習題 (三個變數值交換)
### 題目: 交換前： a = 40 , b = 20 , c = 100 交換後： a = 20 , b = 100 , c = 40
```
#include <stdio.h>
#include <stdlib.h>

int main(void){

    int a = 40   ; //宣告變數a值 
    int b = 20   ; //宣告變數b值
    int c = 100  ; //宣告變數c值
    int temp = 0 ; //宣告暫存變數 

    printf("交換前： a = %d , b = %d , c = %d\n",a,b,c);
	
    temp = a ; // a 傳給 temp   
    a  =  b ;  //b 傳給 a 
    b  =  c ;  //c 傳給 b 
    c = temp ; //temp 傳給 c 
    printf("交換後： a = %d , b = %d , c = %d\n",a,b,c);
  
    system("pause"); //停留畫面 
    return 0 ;       //程式結束 回傳 0 
	
}
```
### 執行結果
```
交換前： a = 40 , b = 20 , c = 100
交換後： a = 20 , b = 100 , c = 40
```
 
