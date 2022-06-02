# Linked List Insertion Lab

## Lab Instructions

In this lab we will be practicing how to insert an object to the end of our Custom Linked List class located in `src/main/java/CustomLinkedList.java`. 

We will implement the `add()` method which will add an object to the end of the list. This method will allow for any number of element to be added sequentially to this list. Be sure to **increment the size** with each successful iteration.

## Running the Tests

The lab comes with tests that will verify the correct functionality. You can look at the test code to get a better sense of what the lab expects located in `src/test/java/CustomLinkedListTest.java`. 

To run the tests, use Maven via your shell with `mvn test` or in your IDE. The **Run** button on Replit should also run your tests. 

Without editing any code, your first test run should give you output similar too:

```
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running CustomLinkedListTest
[ERROR] Tests run: 5, Failures: 2, Errors: 3, Skipped: 0, Time elapsed: 0.018 s <<< FAILURE! - in CustomLinkedListTest
[ERROR] whenMultipleItemsAddedToNewListCountIsCorrect  Time elapsed: 0.011 s  <<< FAILURE!
org.opentest4j.AssertionFailedError: expected: <true> but was: <false>
	at CustomLinkedListTest.whenMultipleItemsAddedToNewListCountIsCorrect(CustomLinkedListTest.java:85)

[ERROR] whenValidItemAddedToNewListHeadIsAssigned  Time elapsed: 0.001 s  <<< ERROR!
java.lang.NullPointerException: Cannot invoke "Object.getClass()" because "o" is null
	at CustomLinkedListTest.whenValidItemAddedToNewListHeadIsAssigned(CustomLinkedListTest.java:34)

[ERROR] whenValidItemsAddedToNewListOrderIsCorrect  Time elapsed: 0.001 s  <<< ERROR!
java.lang.NullPointerException: Cannot invoke "Object.getClass()" because "o" is null
	at CustomLinkedListTest.whenValidItemsAddedToNewListOrderIsCorrect(CustomLinkedListTest.java:68)

[ERROR] whenValidItemAddedToNewListItIsNoLongerEmpty  Time elapsed: 0.001 s  <<< FAILURE!
org.opentest4j.AssertionFailedError: expected: <false> but was: <true>
	at CustomLinkedListTest.whenValidItemAddedToNewListItIsNoLongerEmpty(CustomLinkedListTest.java:21)

[ERROR] whenValidItemAddedToNewListDataIsPresent  Time elapsed: 0 s  <<< ERROR!
java.lang.NullPointerException: Cannot invoke "Object.getClass()" because "o" is null
	at CustomLinkedListTest.whenValidItemAddedToNewListDataIsPresent(CustomLinkedListTest.java:48)
  ```

If you have any issues, try running `mvn dependency:resolve` and then running the tests again. 

If that doesn't work, let avi@revature.com know and do your best without the tests.

## GitHub

You can also fork and clone this lab on [GitHub](https://github.com/revature-curriculum/linked-list-insertion-lab-java) and submit a pull request when you're done.