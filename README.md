# Lab3
Домашняя работа к лабораторной работе №3

# Условия задачи
Написать и отладить программу пересчёта килограмм в фунты и унции

# Блоксхема

<img width="161" height="801" alt="Диаграмма без названия drawio" src="https://github.com/user-attachments/assets/39918217-0db1-456c-a7fe-15cfae1d7035" />

# Реализация программы

```
#include<stdio.h>
#include<locale.h>
#define F 2.2046226
#define U 35.27396

float kg, f, u;

void main()
{
	setlocale(LC_ALL, "RUS");
	printf("Введите число килограмм\n");// Задание 30
	scanf("%f", &kg);
	f = F * kg; // Фунты
	u = U * kg; // Унции
	printf("%f килограмм - %f фунтов\n", kg, f);
	printf("%f килограмм - %f фунтов\n", kg, u);
	


}
```

# Результат программы

<img width="1102" height="637" alt="image" src="https://github.com/user-attachments/assets/49376c79-cf24-4cf1-859f-939f68cbe6f8" />
