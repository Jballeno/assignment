"# assignment" 
package GitHub;

public class assignment {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
//1 create array
 int[] ages = {3, 9, 23, 64, 2, 8, 28, 93};
 
//1A subtract first element from the last
 int minus = (ages[ages.length - 1] - ages[0]);
 System.out.println(minus);
 
 //1B new Age
 int[] ages2 = {3, 9, 23, 64, 2, 8, 28, 93, 95};
 int minus2 = ages2[ages2.length - 1] - ages2[0];
 System.out.println(minus2);
 
 //1C
 double sum = 0;
 
 for(int a : ages) {
	 sum+=a;
 }
 System.out.println(sum / ages.length);
 
 //Question2
 String [] names = {"sam", "Tommy", "Tim", "Sally", "Buck", "Bob"};
 
 //2A use loop
 	int sumAvg = 0;
 	for ( int i = 0; i < names.length; i++) {
 		sumAvg += names[i].length();
 	}
 	int average = sumAvg / names.length;
 //	System.out.println(average);
 	
 	
 	//2B b.	Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
 //	String concatedNames = "";
 //	for (int i = 0; i <names.length; i++) {
 //		concatedNames += (names[i] + " ");
 		
 		// System.out.println(concatedNames);
 		
 		
 		//Question 3: b.	Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
 		// arrayName[arrayName.length - 1]
 		
 		//Question 4:b.	Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
 		// arrayName[0]
 		
 		//Question 5: b.	Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
 		int [] namesLength = new int[names.length];
 		
 		for ( int i = 0; i < names.length; i++) {
 			namesLength[i] = names[i].length();
 			// System.out.println();
 		}
 		for ( int x : namesLength) {
 			// System.out.println(x);
 		}
 
 		//Question 6	Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
 		int sumElements = 0;
 		for ( int i =0; i < namesLength.length; i++) {
 			sumElements += namesLength[i];
 		}
 		//System.out.println(sumElements);
	}
	//Question 7
	public static String concatWords(String word, int n) {
		
		String answer = "";
		for (int i = 0; i < n; i++) {
			answer += word;
		}
		return answer;
	}

	//Question 8
	public static String fullName(String firstName, String lastName) {
		String fullName = firstName + " " + lastName;
		return fullName;
	}
	
	//Question 9
public static boolean validate(int array) {
	int [] numArray = new int [array];
	
	int sumArray = 0;
	for ( int i =0; i < numArray.length; i++) {
		sumArray += numArray[i];
		}
	if (sumArray > 100) {
		return true;
	} else {
		return false;
	}
}

	//Question 10 b.	Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
	public static double doubleAvg (int averageNumbers) {
		double [] avgNumber = new double[averageNumbers];
		
		double douAvg = 0;
		
		for ( int i = 0; i < avgNumber.length; i++) {
			douAvg += avgNumber[i];
		}
		double averageNum = douAvg / avgNumber.length;
		return averageNum;
	}
		//Question 11
		public static boolean arrayTest(int one, int two) {
			double [] doubOne = new double[one];
			double [] doubTwo = new double[two];
			
			double doubAvgOne = 0;
			double doubAvgTwo = 0;
			
			for (int i = 0; i < doubOne.length; i++) {
				doubAvgOne += doubOne[i];
			}
			double avgNumOne = doubAvgOne / doubOne.length;
			for( int i = 0; i < doubTwo.length; i++) {
				doubAvgTwo += doubTwo[i];
			}
			double avgNumTwo = doubAvgTwo / doubTwo.length;
		
			if (avgNumOne > avgNumTwo) {
				return true;
			} else {
				return false;
			}
		}
		//Question 12 Use a loop to iterate through the array again and concatenate all the names together, separated by spaces, and print the result to the console.
		public static boolean willBuyDrink(boolean isHotOutside, double moneyInPocket) {
			if (isHotOutside == true && moneyInPocket > 10.50) {
				return true;
			} else {
				return false;
			}
		}
		
		//Question 13
		
		public static boolean getCoffee( double moneyOnGiftCard, boolean noCoffeeAtHome) {
			if (moneyOnGiftCard >= 7.50 && noCoffeeAtHome ==true) {
				return true;
			} else {
				return false;
			}
		}
}


