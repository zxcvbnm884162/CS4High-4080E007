# 4-1 計算 鈔票 與 硬幣
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int Milk_tea = 35 ;        //奶茶        35元 
    int black_tea = 20;        //紅茶        20元 
    int Cappuccino = 50 ;      //卡布奇諾    50元 
    int Coffee_latte = 80 ;	   //咖啡拿鐵    80元 
    int Pearl_milk_tea = 45 ;  //珍珠奶茶    45元 
    int Winter_melon_tea = 30 ;//冬瓜茶      30元 
    int Pudding_milk_tea = 60 ;//布丁奶茶    60元 
    int Alishan_Iced_Tea = 100;//阿里山冰茶 100元 
	
    int total ; //總額 
    int temp1 ; //商數 
    int temp2 ; //餘數 
	
    total = Milk_tea * 5 + black_tea * 10 + Cappuccino * 5 	+ Coffee_latte * 1 + Pearl_milk_tea * 5 + Winter_melon_tea * 2
          + Pudding_milk_tea * 3 + Alishan_Iced_Tea * 1 ;
    printf("總共花費： %d 元\n",total);
	
    temp1 = total /1000 ; //除以1000 , 計算要用到幾張千元紙鈔 
    temp2 = total %1000 ; //餘額 
    printf("需要 1000元 紙鈔 %d 張\n",temp1);
	
    temp1 = temp2 /100 ; //除以100 , 計算要用到幾張百元紙鈔  
    temp2 = temp2 %100 ; //餘額 
    printf("需要  100元 紙鈔 %d 張\n",temp1);
	
    temp1 = temp2 /10 ; //除以10 , 計算要用到幾張十元硬幣  
    temp2 = temp2 %10 ; //餘額 都是一元硬幣 
    printf("需要   10元 紙鈔 %d 張\n",temp1);  
    printf("需要    1元 紙鈔 %d 張\n",temp2);
	
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
總共花費： 1270 元
需要 1000元 紙鈔 1 張
需要  100元 紙鈔 2 張
需要   10元 紙鈔 7 張
需要    1元 紙鈔 0 張
```

# 4-2 判別 是否符合 規定
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    char ticket_ready = 'y' ;   //機票準備好了
    char passport_ready = 'y' ; //準備好護照
	
    int  go_abroad ;

    printf("\n護照辦好了嗎? <請輸入y or n>： \n");
    passport_ready = getche();
	
    printf("\n機票買好了嗎? <請輸入y or n>： \n");
    ticket_ready = getche();
	
    go_abroad = passport_ready == 'y' && ticket_ready == 'y';
    printf("\n\n 1代表可出國 , 0代表很抱歉： %d\n\n",go_abroad);
		
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
<1> 第一種執行結果                    <2> 第二種執行結果                    <3> 第三種執行結果

護照辦好了嗎? <請輸入y or n>：        護照辦好了嗎? <請輸入y or n>：       護照辦好了嗎? <請輸入y or n>：
y                                    n                                  y
機票買好了嗎? <請輸入y or n>：        機票買好了嗎? <請輸入y or n>：       機票買好了嗎? <請輸入y or n>：
y                                    y                                  n
1代表可出國 , 0代表很抱歉： 1         1代表可出國 , 0代表很抱歉： 0        1代表可出國 , 0代表很抱歉： 0

```

# 4-3 利用 複合 指定運算式 計算複合
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    float interest = 0.02 ;       //年利率 2%
    float principal = 1000000.0 ;  //本金

    printf("本金 1000000元 , 年利率 2%% , 計算五年後本利和\n");
	
    printf("一年後的本利和 = %-9.0f\n",principal = principal * (1+interest));
    printf("一年後的本利和 = %-9.0f\n",principal = principal * (1+interest));
    printf("一年後的本利和 = %-9.0f\n",principal = principal * (1+interest));
    printf("一年後的本利和 = %-9.0f\n",principal = principal * (1+interest));
    printf("一年後的本利和 = %-9.0f\n",principal = principal * (1+interest));
	
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
本金 1000000元 , 年利率 2% , 計算五年後本利和。
一年後的本利和 = 1020000
一年後的本利和 = 1040400
一年後的本利和 = 1061208
一年後的本利和 = 1082432
一年後的本利和 = 1104081
```

# 4-4 判斷 是否為 英文字母
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int uppercase , lowercase ; //宣告 大寫 與 小寫 
    char ch ; 
	
    printf ("請輸入一個英文字母： ");
    ch = getchar(); 
    printf ("您輸入的是 %c\n",ch);
	
    uppercase = ch > 64 && ch < 91  ; //判斷是否為 '大寫' 
    lowercase = ch > 96 && ch < 123 ; //判斷是否為 '小寫' 
	
    printf("輸出 1 表示是英文字母 , 輸出 0 表示不是英文字母： ");
    printf("%d\n",uppercase || lowercase);
	
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
<1> 第一種執行結果                                      <2> 第一種執行結果

請輸入一個英文字母： a                                  請輸入一個英文字母： 1
您輸入的是 a                                           您輸入的是 1
輸出 1 表示是英文字母 , 輸出 0 表示不是英文字母： 1       輸出 1 表示是英文字母 , 輸出 0 表示不是英文字母： 0
```

# 4-5 代幣的轉換
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int coin ;             //代幣 轉 現金 
    int ten , five , one ; //轉換 十元 五元 一元
	
    printf("請輸入您的代幣總共多少： ");
    scanf ("%d",&coin);
	
    ten = coin / 10 ;     //計算 十元 
    five = coin % 5 /5 ;  //計算 五元 
    one = coin %10 %5 ;   //計算 一元 
	
    printf("\n可領回： \n 十元：%d 個 \n 五元： %d 個 \n 一元： %d 個\n",ten,five,one);
	
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
請輸入您的代幣總共多少： 218

可領回：
 十元：21 個
 五元： 1 個
 一元： 3 個
```
