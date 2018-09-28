---
title: "How to JAVA star shrape typing"
date: 2018-9-28 09:26:28 -0400
categories: Java Developer Program CSS PHP
---


package Report;

public class Report_1 {

	public static void main(String[] args) {
숫자를 입력받아 1부터 입력받은 수까지 홀수의 합과 짝수의 합을 구하세요.
		int num1 = 0, num2 = 0;
		for (int i = 1; i < 21; i++) {
			if (i % 2 == 0) {
				num1 += i;
			} else if (i % 2 != 0) {
				num2 += i;
			}
		}
		System.out.println("짝수의 합은" + num1 + ", " + "홀수의 합은" + num2 + "입니다.");

직각이 오른쪽에 있는 삼각형 모양의 별을 출력해주세요.

		for (int i = 1; i < 6; i++) {
			for (int j = 5; j > 0; j--) {
				if (i < j) {
					System.out.print(" ");
				} else {
					System.out.print("*");
				}
			}
			System.out.println();
		}
		System.out.println();

직각이 오른쪽에 있는 역삼각형 모양의 별을 출력해주세요.

		for (int i = 0; i < 5; i++) {
			for (int j = 0; j < i; j++) {
				System.out.print(" ");
			}
			for (int j = 0; j < 5 - i; j++) {
				System.out.print("*");
			}
			System.out.println();
		}

이등변 삼각형 모양의 별을 출력해주세요.

		for (int i = 0; i < 4; i++) {
			for (int j = 0; j < 3 - i; j++) {
				System.out.print(" ");
			}
			for (int j = 0; j < 2 * i + 1; j++) {
				System.out.print("*");
			}
			System.out.println();
		}
		
		System.out.println();

		
		
역 이등변 삼각형 모양의 별을 출력해주세요.
		int k1 = 0, k2 = 9;

		for (int i = 0; i < 5; i++) {

			for (int j = 0; j < k1; j++) {
				System.out.print(" ");
			}

			for (int j = 0; j < k2; j++) {
				System.out.print("*");
			}

			k1++;
			k2 -= 2;

			System.out.println();

		}
	}
}
