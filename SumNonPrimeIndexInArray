import java.io.*;
import  java.util.*;

// Read only region start
class UserMainCode
{

	public int sumOfNonPrimeIndexValues(int[] input1,int input2){
		// Read only region end
		// Write code here...
		ArrayList<Integer> ar = new ArrayList<>();
		ar.add(input1[0]);
		ar.add(input1[1]);
		for(int i=2;i<input2;i++){
			boolean isprime = true;
			for(int j=2;j<=i/2;j++){
				if(i%j==0){
					isprime=false;
					break;
				}
			}
			if(isprime==false){
				
				ar.add(input1[i]);
			}
		}
        int sum=0;
		for(int d:ar){
		     sum+=d;
		}
		
		return sum;
	}
}
