//compro_week4

#include <stdio.h>

int main() {

//ประกาศตัวแปรสำหรับข้อมูลส่วนบุคคล
char name[30]; //ชื่อ
int age; //อายุ
float height; //ส่วนสูง

//ประกาศตัวแปรข้อมูลเครื่องดื่ม
char drink; //เครื่องดื่ม
float price; //ราคา
char size; //ขนาดแก้ว

//รับข้อมูลบรรทัดที่1
scanf("%s %d %f", name, &age, &height);

//รับข้อมูลบรรทัดที่2
scanf(" %c %f %c", &drink, &price, &size);

//แสดงข้อมูลส่วนบุคคล
printf("%s is %d years old and is %.1f cm tall.\n", name, age, height);

//แสดงข้อมูลเครื่องดื่ม
printf("Favorite drink %c costs %.2f baht and has size %c.\n", drink, price, size);

//จบการทำงาน
return 0;
}