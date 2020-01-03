### printf()
```
此函式將指定的字串以指定的格式輸出。
```

### putchar()
```
此函式的用途是輸出字元，且只能輸出一個字元，不具備輸出功能。
```

### scanf()
```
透過鍵盤輸出資料，並且按下Enter,才會讀入資料。
```

###  getchar()
```
透過鍵盤輸出資料，並且按下Enter，並讀取資料的第一個字元。
```

### getche()
```
透過鍵盤輸入字元，不用按Enter直接讀取。
```

### getch()
```
透過鍵盤輸入字元，但是不會顯示輸入的字元，不用按Enter直接讀取。
```

# 3-1 輸出的字串被切斷
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    printf("請輸入密碼： \0 密碼是我的身分證字號\n"); //使用 \0 切斷字串 
	
    system("pause"); //停留畫面 
    return 0;  //程式結束 回傳 0 
	
} 
```
### 執行結果
```
請輸入密碼：
```

# 3-2 鍵盤輸出字元 + 十六進位值
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int ASCII ; //宣告 ASCII 碼
	
    printf("請從鍵盤輸入一個字元 , 並按 Enter 鍵 \n");
    ASCII = getchar(); //讀取鍵盤輸入的字元
	
    printf("你剛剛輸入的 ASCII 碼是：");
    putchar(ASCII);
    printf("\n%c 的 ASCII 碼是  %d\n",ASCII,ASCII);
    printf("%c 的十六進位值是 %x\n",ASCII,ASCII);
	
    system("pause");
    return 0;
    
} 
```
### 執行結果
```
請從鍵盤輸入一個字元 , 並按 Enter 鍵
W
你剛剛輸入的 ASCII 碼是：W
W 的 ASCII 碼是  87
W 的十六進位值是 57
```

# 3-3 輸入字元 , 列印組成的圖形
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    char c ; //宣告一個字元變數 
	
    printf("請輸入一個字元：");
    c = getche();
	
    printf("\n\n");
	
    printf("%c %c %c %c %c %c %c %c\n",c,c,c,c,c,c,c,c);
    printf("%c %c %c %c %c %c %c\n",c,c,c,c,c,c,c);
    printf("%c %c %c %c %c %c\n",c,c,c,c,c,c);
    printf("%c %c %c %c %c\n",c,c,c,c,c);
    printf("%c %c %c %c\n",c,c,c,c);
    printf("%c %c %c\n",c,c,c);
    printf("%c %c\n",c,c);
    printf("%c\n",c);
		
    system("pause");
    return 0;
	
} 
```
### 執行結果
```
請輸入一個字元：*

* * * * * * * *
* * * * * * *
* * * * * *
* * * * *
* * * *
* * *
* *
*
```

# 3-4 數字計算
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int number1 , number2 ; //宣告兩個整數的變數 
	
    printf("請輸入兩個整數：");
    scanf ("%d %d \n",&number1,&number2);
	
    printf("你輸入的兩個整數是 %d 與 %d \n",number1,number2);
    printf("兩數整數相加為 %d \n",number1+number2);
	
    system("pause");
    return 0;
	
} 
```
### 執行結果
```
請輸入兩個整數：2 3
你輸入的兩個整數是 2 與 3
兩數整數相加為 5
```

# 3-5 讀取 年齡 與 性別
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int age    ; //宣告 短整數 為 age 
    char gender; //宣告 字串型態 為 gender 
	
    printf("請輸入年齡： ");
    scanf ("%d",&age); //讀取第一個 scanf 的數字 
	
    printf("請輸入性別<男：M 女：F> ： ");
    gender = getche(); //讀取第二個字元 
	
    printf("\n");
	
    printf("您是 %d 歲的 %c \n",age,gender);
	
    system("pause");
    return 0;
	
} 
```
### 執行結果
```
請輸入兩個整數：2 3
你輸入的兩個整數是 2 與 3
兩數整數相加為 5
```






