### Unit Test and TDD

_Test Driven Development_ (TDD) is a software development practice that focuses on creating unit test cases before developing the actual code. It is an iterative approach combining programming, unit test creation, and refactoring.

<img src="https://browserstack.wpenginepowered.com/wp-content/uploads/2023/06/TDD-320x385.png" alt="Description of the image" style="width:300px; height:200px;"><br/><br/>

**Steps of TDD**   
 
**Write a Test:**   
Before writing any code, we need to write a test that defines the expected behaviour of the feature we are about to implement. This test will initially fail because the feature doesn't exist yet.

**Run the Test:**  
 Run your test. Since we haven't implemented the feature yet, the test should fail. This confirms that our test is working correctly and that we are testing the right thing. 

**Write Code:**   
Now we have to write the minimum code necessary to make the test pass. We're not concerned with writing perfect or optimized code at this point; our focus is on making the test pass.

**Run Tests Again:**  
 After writing the code, we rerun our tests. If our test passes, it means our new code is functioning as expected and hasn't broken any existing functionality.

**Refactor (Optional):**  
 With passing tests, we can refactor our code to improve its structure, readability, and performance. The key here is that our tests act as a safety net, ensuring that our changes don't introduce bugs.

**Repeat:**  
 We repeat this cycle, writing new tests for new features or modifications, running tests, writing code, and refactoring as needed.  

 **Example**  
 Let's take an example for testing the ``` add()``` function, which will add the number and return the result using **JEST**.

 **Step 1** : 
 *write the first test case* 
```typescript
 describe("test add fun",()=>{

    it("should exist",()=>{
        expect(add).toBeTruthy();
    })
  }
```
*Test case* **FAIL**  

**Step 2** *Write the function to pass the test case* 
*Source code*  
```typescript 
export function add(){

}
```
Run the test case  

Test case **PASS**  

**Step 3**



