# Amicom C 스터디 연습장

- 아미콤 C 스터디 전용 레포지토리입니다.
- 매 주차마다 학습 내용과 실습 내용을 README 파일과 각자의 C 파일에 자유롭게 작성합니다.
- 정해진 작성 형식은 없습니다.

## 1주차 배운 내용
    #include <stdio.h>

    int main() {
        int days_in_year = 365;
        double circumference_rate = 3.1415926535;
        int a1, a2;

        printf("Total days in year: %d\n", days_in_year);
        printf("Circumference rate: %lf\n", circumference_rate);

        printf("Enter two integers: ");
        scanf_s("%d %d", &a1, &a2);
        printf("You entered: %d %d\n", a1, a2);

        return 0;
    }

## 2주차 배운 내용

1번
    
    #include <stdio.h>

    int main() {
        int n;
        scanf_s("%d", &n);

        if ((n % 2 == 1 && n % 3 == 0) || (n % 2 == 0 && n % 5 == 0)) {
            printf("true");
        }
        else {
            printf("false");
        }

        return 0;
    }
2번
    
    #include <stdio.h>

    int main() {
        int n;
        scanf_s("%d", &n);

        if (n % 2 == 1 && n < 5) {
            printf("A");
        }
        else if (n % 2 == 1 && n >= 5) {
            printf("B");
        }
        else {
            printf("C");
        }

        return 0;
    }
3번
    
    #include <stdio.h>

    int main() {
        int i, j;
        for (i = 1; i <= 5; i++) {
            for (j = 1; j <= i; j++) {
                if (i % 2 == 1) {
                    printf("*");
                }
            }
            printf("\n");
            if (i % 2 == 1) {
                printf("$\n");
            }
        }
        return 0;
    }

## 3주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 4주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 5주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 6주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 7주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 8주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 9주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 10주차 배운 내용
- 이곳에 작성하시면 됩니다.
