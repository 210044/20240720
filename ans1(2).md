## 提示詞2 Chat GPT的回應

#include <stdio.h>

int main() {
    int i, j;
    
    // 打印九九乘法表
    for (i = 1; i <= 9; ++i) {
        for (j = 1; j <= i; ++j) {
            printf("%d * %d = %d\t", j, i, j * i);
        }
        printf("\n");
    }
    
    return 0;
}
