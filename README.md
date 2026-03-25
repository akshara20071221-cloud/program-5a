# program-5a
# 🧪 C Programming Lab
## 📘 Experiment No: 5a
### 🔹
**Date:** 23/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
 To write a C program to multiply three numbers using pointers.
---

## 🧠 ALGORITHM
1.Get three numbers as inputs from the user.
2.Assign pointer variables for each inputs.
3.print the result of multiplication using printf() funtion.
---

## 💻 PROGRAM

```
#include<stdio.h>
int main()
{
    int num1,num2,num3;
    scanf("%d %d %d",&num1,&num2,&num3);
    int *ptr1=&num1,*ptr2=&num2,*ptr3=&num3;
    printf("%d * %d * %d= %d",num1,num2,num3,*ptr1**ptr2**ptr3);
}

```

## 🖼️ OUTPUT SCREENSHOT
<img width="576" height="304" alt="image" src="https://github.com/user-attachments/assets/eb646bda-470a-41a9-b4af-dc4f43ce2e92" />


---

## ✅ RESULT
: Thus the C program to multiply three numbers using pointers is executed successfully.
