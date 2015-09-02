/* 
 * Project: ExtendedGrader.java
 * Description: A program that reports letter grades (and other things)
 * Author: Hanmin Yun
 * Date: August 31, 2015
 */

import java.util.Scanner; // gest user input

class ExtendedGrader {
  
  public static void main( String[] args ) {
    
    Scanner s = new Scanner( System.in );
    int grade;
    
    System.out.println( "Enter your grade percentage: " );
    grade = s.nextInt(); // input the user grade
    
    // Extended else-if to output the letter grade
    if ( grade >= 90 ) { // if greater than 90%
      System.out.println( "You got an A!" );
      
    } else if ( grade >= 80 ) { // if less than 90% but greater than 80%
      System.out.println( "You got a B~");
      
    } else if ( grade >= 70 ) { // if less than 80% but greater than 70%
      System.out.println( "You got a C.");
      
    } else if ( grade >= 60 ) { // if less than 70% but greater than 60%
      System.out.println( "You got a D...");
      
    } else {
      System.out.println( "You got an F. Loser..." );
      
    }
    
    /*
     * Challenge: Create an if-else that tells the user "Congrats!"
     * if their grade is greater than 100 (bonus points). Or
     * "You're a normal student." if under 100.
     */
    
    if ( grade >= 100) {
      System.out.println( "Congrats!" );
    } else {
      System.out.println( "You are a normal student." );
    }
    
    /*
     * Challenge: Using an if-else, tell the user whether
     * their grade is "positive" or "negative" or "zero".
     */
    
    if ( grade == 0) {
      System.out.println( "Zero" );
    } else if ( grade > 0 ) {
      System.out.println( "Positive" );
    } else {
      System.out.println( "Negative" );
    }
    
    /*
     * Challenge: Make the computer print EXACTLY the following:
     * 
     * From: Bill Smith
     * Address: Dell Computer, Bldg 13
     * Date: April 12, 2005
     * 
     * To: Jack Jones
     * 
     * Message: Help! I'm trapped inside a computer!
     */
    // Using multiple System.outs
    System.out.println( "From: Bill Smith" );
    System.out.println( "Adress: Dell Computer, Bldg 13" );
    System.out.println( "Date: April 12, 2015" );
    System.out.println( "" );
    System.out.println( "To: Jack Jones" );
    System.out.println( "" );
    System.out.println( "Message: Help! I'm trapped inside a computer!" );
    
    
  } // end main method
  
} // end class