#### Write your implementation of testing framework and assertion. Only after completing this go forward.

#### Write two tests for the following functions using test framework assertion

#### Add two number

1. Write a function that takes two input `numA` and `numB` and returns the sum of both numbers.
2. After writing the function write 5 tests for above function with different values
3. Throw an error when the arguments passed in not a number.
4. Make first test fail and see if you get the result of second test.
5. If not fix it using the test framework (try...catch) we learned in the testing framework video.


function testAdd(){
  result = add(2,4);
  expected = 5;
  if(result !== expected) {
    throw new Error(`${result} is not equal to ${expected}`);

  }
}
test("adding 2 and 4", testAdd);


function subTest(){
  result = add(20,4);
  expected = 15;
  if(result !== expected) {
    throw new Error(`${result} is not equal to ${expected}`);

  }
}
test("subtracting 20 and 4", subTest);


#### Multiply two numbers

1. Write a function that takes two input `numA` and `numB` and returns the multiplication of both numbers.
2. After writing the function write 5 tests for above function with different values
3. Throw an error when the arguments passed in not a number.
4. Make first test fail and see if you get the result of second test.
5. If not fix it using the test framework (try...catch) we learned in the testing framework video.


