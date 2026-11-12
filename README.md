# DA26TTA-KTLT-110126097

#include<stdio.h>

int main(){
	int a,b;
	
	printf("nhap so nguyen thu nhat (a):");
	scanf("%d",&a);
	printf("nhap so nguyen thu hai(b):");
	scanf("%d",&b);
	
	printf("Tong: %d + %d= %d\n",a,b,a+b);
		printf("Tong: %d - %d= %d\n",a,b,a-b);
			printf("Tong: %d * %d= %d\n",a,b,a*b);
			
			if(b!=0){
				printf("Thuong: %d / %d= %.2f\n",a,b,(float)a/b);
				
			}else{
				printf("THuong: Khong the chia cho 0!\n");
			}
	
	
	return 0;
}
