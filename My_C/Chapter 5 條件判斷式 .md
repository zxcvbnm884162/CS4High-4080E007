# 5-1 判斷 kpi 是否達成 與 年資是否在一年內

### if 條件判斷
```
if (條件算式){
  動作程式
}
```

### 程式設計
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    float salary = 2220.56 ; //薪水金額
    float kpi = 1.5 ;        //kpi 達成率 150%
    float bonus ;            //宣告 獎金 變數
    float seniority = 0.9 ;  //年資0.9年 
	
    if (kpi >= 0.85 && seniority < 1){
	
        bonus = salary * kpi * kpi * kpi + 2000 ;
        printf("年資未滿 1 年優秀員工 , 恭喜獲得 kpi 獎金為 %6.2f \n",bonus);
        
    }
	
    if (kpi >= 0.85 && seniority >= 1){
	
        bonus = salary * kpi * kpi * kpi ;
        printf("恭喜獲得 kpi 獎金為 %6.2f \n",bonus);
		
    }
    
    printf("祝新年快樂\n");
	
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
年資未滿 1 年優秀員工 , 恭喜獲得 kpi 獎金為 9494.39
祝新年快樂
```
	
# 5-2 判斷杯數是否達到打折標準

### if-else 條件判斷
```
if (條件算式){
  動作程式 1
}
else{
  動作程式 2
}
```

### 程式設計
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int Cappuccino = 50 ;    //宣告 卡布奇諾 初值為 50元 
    int cup_Cappuccino = 1 ; //宣告 卡布奇諾 杯數為  1杯 
    int total_price = 0 ;    //宣告 結帳金額 變數 初值為 0 

    printf("卡布奇諾 原價 %d元 , 買 10 杯 打 9 折 \n請問您要買幾杯： ",Cappuccino);
    scanf ("%d",&cup_Cappuccino);	

    //小於 10 杯算原價 ,  大於 等於 10 杯 打9折 
	
    if (cup_Cappuccino < 10)
        total_price = Cappuccino * cup_Cappuccino ;
	
    else 
        total_price = Cappuccino * 0.9 * cup_Cappuccino ;
	
	
    printf("帳單：\n");
    printf("卡布奇諾 %d 杯 %d 元\n",cup_Cappuccino,total_price);
  
    system("pause");
    return 0;
		
}
```
### 執行結果
```
卡布奇諾 原價 50元 , 買 10 杯 打 9 折
請問您要買幾杯： 20
帳單：
卡布奇諾 20 杯 900 元
```

# 5-3 將成績 轉換成 GPA分數

### if-else if 條件判斷
```
if (條件算式 1){
  動作程式 1
}
else if (條件算式 2) {
  動作程式 2
}
else if (條件算式 3) {
  動作程式 3
}
--------------------------
依情況而定，可做省略。

else{
  最後動作程式
}

```

### 程式設計
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int grade ; //宣告 成績 變數
	
    printf("請輸入成績： ");
    scanf ("%d\n",&grade);
	
    if (grade >= 80){
        printf("優秀的 A 級 , GPA 為 4 \n");
    }
	
    else if (grade < 80 && grade >= 70){  
        printf("不錯的 B 級 , GPA 為 3 \n");
    } 
	
    else if (grade < 70 && grade >= 60){
        printf("及格的 C 級 , GPA 為 2 \n");
    } 

    else if (grade < 60 && grade >= 50){  
        printf("加油的 D 級 , GPA 為 1 \n");
    } 
	
    else {
	printf("重考的 E 級 , GPA 為 0 \n"); 
	printf("希望還有機會遇見你! \n"); 
    }
	
    system("pause"); 
    return 0;
				
}
```
### 執行結果
```
<1> 第一種執行結果          <2> 第一種執行結果

請輸入成績： 85             請輸入成績： 45
優秀的 A 級 , GPA 為 4      重考的 E 級 , GPA 為 0
                           希望還有機會遇見你!
```

# 5-4 判斷 TOEIC 成績 是否達到畢業標準

### if 巢狀 條件判斷
```
if (條件算式 1){
    if (條件算式 2){
    } 
}
else {
    if (條件算式 3){
    }
}
```

### 程式設計 
```
#include <stdio.h>
#include <stdlib.h>

int main(void){

    char TOEIC_exam ; //詢問是否有考 多益英文測驗 
    char gradeuate ;  //是否知道要考 多益英文測驗 
    int  score     ;  //紀錄 多益英文測驗 的 成績 
	
    printf("你有考 TOEIC 嗎? <y/n> ： ");
    TOEIC_exam = getche();
	
    if  (TOEIC_exam == 'y' || TOEIC_exam == 'Y'){
		
	printf("\n請輸入考幾分： ");
	scanf ("%d\n",&score);
		
	if (score > 800){
	
	    printf("恭喜通過!\n");		
	else
	    printf("再加油!!!");	
	    
	}
	
	else {
		
	    printf("\n你知道沒通過不能畢業嗎? <y/n> ： ");
            gradeuate = getche();
		
            if(gradeuate == 'y' || gradeuate == 'Y')
	        printf("\n記得再去考一次!\n");	
	    else
		printf("\n現在你知道了吧!\n");
			
	}
		
	system("pause");
	return 0;
				
}
```
### 執行結果
```
<1> 第一種執行結果                <2> 第二種執行結果                      <3> 第三種執行結果
你有考 TOEIC 嗎? <y/n> ： y      你有考 TOEIC 嗎? <y/n> ： n             你有考 TOEIC 嗎? <y/n> ： n
請輸入考幾分： 900               你知道沒通過不能畢業嗎? <y/n> ： n       你知道沒通過不能畢業嗎? <y/n> ： y
恭喜通過!                        現在你知道了吧!                         記得去考!
```

# 5-5 電話區碼判斷是哪個區域 

### switch-case 條件判斷
```
switch (條件算式){

   case 條件算式值 1 :
        動作程式 1 ;
   break ;

   case 條件算式值 2 :
        動作程式 2 ;
   break ;
   
   case ......
   
   default:
        例外動作程式 ;
}
```

### 程式設計
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int Area_code ; //宣告 存放區碼變數 為 Area_code 
	
    printf("請輸入電話區域號碼： ");
    scanf ("%d\n",&Area_code);
	
    switch(Area_code){
		
	case 1:{
		printf("01   是保留號");
	break;
	}
	
	case 2:{
		printf("02   是台北、新北、基隆 的區域號碼\n") ;
	break;
	}		
	
	case 3:{
		printf("03   是桃園、新竹、宜蘭、花蓮 的區域號碼\n");
	break;
	}	
 	
 	case 37:{
		printf("037  是苗栗的區域號碼\n");
	break;
	}	
	 
 	case 4:{
		printf("04   是台中、彰化 的區域號碼\n");
	break;
	}
		
	case 49:{
		printf("049  是南投的區域號碼\n");
	break;
	}
		
	case 5:{
		printf("05   是雲林、嘉義 的區域號碼\n");
	break;
	}
		
	case 6:{
		printf("06   是台南、澎湖 是區域號碼\n");
	break;
	}
	
	case 7:{
		printf("07   是高雄的區域號碼\n");
	break;
	}
	
	case 8:{
		printf("08   是屏東的區域號碼\n");
	break;
	}
		
	case 89:{
		printf("089  是台東的區域號碼\n");
	break;
	}
		
	case 82:{
		printf("082  是金門的區域號碼\n");
	break;
	}
		
	case 826:{
		printf("0826 是烏坵的區域號碼\n");
	break;
	}
		
	case 836:{
		printf("0836 是馬祖的區域號碼\n");
	break;
	}
		
	default:{
		printf("查無此號碼，請再檢查一遍。\n");	
	break;
	}
		
system("pause");
return 0 ;
	
     }
	
} 
```
### 執行結果
```
請輸入電話區域號碼： 05
05   是雲林、嘉義 的區域號碼
```
