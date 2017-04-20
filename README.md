# Calculator-
Codecademy freeform project

public class Calculator {
  public Calculator() {}
  int add(int a, int b) {
      return a + b;
    }
 		int subtract(int a, int b) {
      return a - b;
		}
    int multiply(int a, int b) {
     return a * b;
    }
   int divide(int a, int b) {
     if(b == 0) {
       System.out.println("Error! Dividing by zero is not allowed."); 
       return 0;
     }
     else {
       return a / b;
     }
   }
   int modulo(int a, int b) {
      if(b == 0) {
        System.out.println("Error! Dividing by zero is not allowed."); 
        return 0;
      }
      else {
        return a % b;
      }
    }
  public static void main(String[] args){
    
  	Calculator myCalculator = new Calculator();
  	System.out.println(myCalculator.add(5,7));
 }
}
