# PrePostDemo

단항연산자/증가연산자(++)


  	package org.opentutorials.javatutorials.operator;

  		public class PrePostDemo {
  
  			public static void main(String[] args) {
		
		
//이항 연산자 infix operator
		
//1+2 두개의 관계를 더하기로 묶어주는 연산자가 + 
//좌항과 우항을 가지고있기 때문에 이항 연산자다.
		
		
		
//단항 연산자
		
//좌항과 우항이 없다.
// +3 이라고하는 뜻은 양수 3이라는 뜻이다.
// -3 은 음수 3이다.
		
//3++ 는 3+1 이라는 뜻이다.
//++는 증가 연산자로 항의 값을 1씩 증가시킨다.
		
// 증가 연산자 (++)에 대해서 살펴보자.
		
		int i = 3;
		
		i++;
		System.out.println(i);  // 4 출력
		
	    	++i;
		
	 	System.out.println(i);  // 5 출력
	    
		System.out.println(++i);  // 6 출력
//++i 는 프린트에도 출력이 되고
		
		System.out.println(i++);  // 6 출력
//i++는 프린트에 출력에 값이 출력되지않고 출력후에 값이 변한다.

		System.out.println(i);  // 7 출력 
//그래서 7이라는 값이 나오게 된다.

//연산의 우선순위

		int a = 4-3*6;
		
//곱하기는 3등급
//더하기나 빼기는 4등급
//= 은 14등급 가장 낮다	
// a = { 4 - ( 3 * 6 ) } 이순서가 된다.
// 최종적으로 - 14가 된다.
		
		System.out.println(a);
		
		
		
		
 }

}
