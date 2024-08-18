# new_naresh1
1.All the code has been written in the respective files .java and Test.java completely with full functionalties.     

2. **Initialize Git Repository:**
   
   git init
   git add .
   git commit -m "Initial project structure"


3. **Write Initial Test (StringCalculatorTest.java):**
   
   import static org.junit.jupiter.api.Assertions.assertEquals;
   import org.junit.jupiter.api.Test;

   public class StringCalculatorTest {
    
       @Test
       public void testAddEmptyString() {
           StringCalculator calculator = new StringCalculator();
           assertEquals(0, calculator.add(""));
       }
   }
   
   Commit the change:
   
   git add .
   git commit -m "Add test for empty string"
   

4. **Implement Code to Pass Test (StringCalculator.java):**
 
   public class StringCalculator {

       public int add(String numbers) {
           if (numbers.isEmpty()) {
               return 0;
           }
           return 0; // Placeholder to pass the initial test
       }
   }

   Commit the change:

   git add .
   git commit -m "Implement add method to handle empty string"


5. **Add More Tests and Incremental Changes (StringCalculatorTest.java and StringCalculator.java):**

   Update the test file and the implementation file as shown above. Make sure to commit after each change.


   git add .
   git commit -m "Add test for single number"
   
   git add .
   git commit -m "Implement code to handle single number"

   git add .
   git commit -m "Add test for two numbers"
   
   git add .
   git commit -m "Implement code to handle two numbers"

   git add .
   git commit -m "Add test for multiple numbers"
   
   git add .
   git commit -m "Implement code to handle multiple numbers"

   git add .
   git commit -m "Add test for new line between numbers"
   
   git add .
   git commit -m "Implement code to handle new line between numbers"

   git add .
   git commit -m "Add test for different delimiter"
   
   git add .
   git commit -m "Implement code to handle different delimiter"

   git add .
   git commit -m "Add test for negative number throws exception"
   
   git add .
   git commit -m "Implement code to throw exception for negative number"

   git add .
   git commit -m "Add test for multiple negative numbers throw exception"
   
   git add .
   git commit -m "Implement code to throw exception for multiple negative numbers"
   

6. **Refactor Code and Commit:**

   git add .
   git commit -m "Refactor code to improve readability"
   

7. **Document Project (README.md):**

   Add the provided README file content, then commit the change.
   
   git add README.md
   git commit -m "Add project documentation"
   

8. **Push Code to GitHub/GitLab:**

   
   git remote add origin [<your-repo-url>]//(https://github.com/Code-experta1/new_naresh1/tree/main)
   git push -u origin master
