### Unit Test and TDD

_Test Driven Development_ (TDD) is a software development practice that focuses on creating unit test cases before developing the actual code. It is an iterative approach combining programming, unit test creation, and refactoring.

<img src="https://browserstack.wpenginepowered.com/wp-content/uploads/2023/06/TDD-320x385.png" alt="Description of the image" style="width:300px; height:200px;"><br/><br/>

**Steps of TDD**   
 
**Write a Test:**   
Before writing any code, we write a test that defines the expected behavior of the feature you're about to implement. This test will initially fail because the feature doesn't exist yet.

**Run the Test:**  
 Run your test. Since you haven't implemented the feature yet, the test should fail. This confirms that your test is working correctly and that you're testing the right thing. 

**Write Code:**   
Now you write the minimum amount of code necessary to make the test pass. You're not concerned with writing perfect or optimized code at this point; your focus is on making the test pass.

**Run Tests Again:**  
 After writing the code, you run your tests again. If your test passes, it means your new code is functioning as expected and hasn't broken any existing functionality.

**Refactor (Optional):**  
 With passing tests, you can refactor your code to improve its structure, readability, and performance. The key here is that your tests act as a safety net, ensuring that your changes don't introduce bugs.

**Repeat:**  
 You repeat this cycle, writing new tests for new features or modifications, running tests, writing code, and refactoring as needed.
