# 210112
package basic;

import java.util.Scanner;

public class CodeUp1566 {

	public static void main(String[] args) {
		f();

	}
	static void f() {
		Scanner sc=new Scanner(System.in);
		int a=sc.nextInt();
		int b=sc.nextInt(); 
		long result=1;
		if(a==1) {
			System.out.println(a);
		}else {
		for (int i = 1; i <= b; i++) {
			result*=a;
		}
		System.out.println(result);
		

	}
	}
}
