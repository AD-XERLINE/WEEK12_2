# WEEK12_2
โปรแกรมรายสัปดาห์ที่ 12 อันที่ 2

    #include <stdio.h>
    void Max(int m,int n){
    	if(m-n>0){
    		printf("%d",m);
    	}
    	else{
    		printf("%d",n);
    	}
    }

    int main() {
    	int i,j;
    	printf("ENTER TWO NUMBER: ");
    	scanf("%d %d",&i,&j);
	
    	Max(i,j);
    }
