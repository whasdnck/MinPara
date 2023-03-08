# MinPara


## MinPara 코드
package sungil21102algo;

public class MinPara {

	static int minpara(int a, int b, int c) {
		int min = a;
		if (b < min)
			min = b;
		if (c < min)
			min = c;
			
			return min;
	}
	
	public static void main(String[] args) {

		System.out.println("minpara(10,9,8)" + minpara(10,9,8));
		System.out.println("minpara(5,15,2)" + minpara(5,15,2));
	}

}
