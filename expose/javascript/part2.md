1. It will print out 3 since it counts how many times the for loop runs based on the prices.length. Since we had 3 elements within the array the i variable was added to 4 times but the for loop ran 3 times since we indexed it to 0. 
2. This will print out 150 since the last number it worked with was the 300 in the array since it was the last number in array. If we were to do the math 
var discountedPrice = prices[i] * (1 - discount);
The last number we used in the array was 300 and the discount was .5 so 300 * .5 = 150 and this number is what was outputed on line 13
3. This will also output 150 since what the finalPrice line does is multiply the discountedPrice by 100, round it, then divide it by 100. So when we multiply round then divide the discountedPrice with 150 it gives us 150 still since we are literlly just multiplying and dividing by 100. 
4. This will output [50, 100, 150] since it will input all the finalPrices into the array thus creating all the possible discounted prices with the given numbers. 
5. This would return an error since let scope doesnt last after the for loop so when we try to print i after the for loop it would be out of the scope.
6. This would also have the same type of error as in 5 where the variable is out of scope. 
7. This would output 150 since it is getting the information from the last element from the array and since it doesnt get declared as a let within the for loop the scope of this variable would last throughout the whole function since it was declared at the beginning of the function. 
8. This will output [50, 100, 150] since it will input all the finalPrices into the array thus creating all the possible discounted prices with the given numbers. 
9. This will return an error since i was declared as a let its scope is only within the for loop.
10. This will return 3 since it will output the length of the prices since we declared it as prices.length. If we were to try to change this value it will thrown an error since we declared it as a constant. and the scope of length is outside of the for loop since we declared it at the start of the function, so we are able to access it outside of the for loop
11. This will return [50, 100, 150] since these are the discounted prices after we do the math within the for loop and pushing it into the discounted array. 
12. 
A. console.log(student.name);
B. console.log(student['Grad Year']);
C. student.greeting();
D. console.log(student['Favorite Teacher'].name);
E. console.log(student.courseLoad[0]);
13. 
A. This is 32 since we are concatenating a 2 onto the 3 since the 3 is in a string form.
B. 1 It successfully converts the '3' into the number 3 allow us to subtract 3-2 to get 1
C. 3 we are literally just adding 3 with nothing.
D. 3null Since 3 is in its string form we are concatenating the 3 with null thus giving us 3null.
E. 4 true = 1 so when we do true + 3 we are basically doing 1 + 3 = 4
F. 0 false = 0 and null is nothing so when we add the 2 together we get 0.
G. 3undefined We are concatenating 3 with undefined, giving us 3undefined.
H. NaN When we subtract the '3' is able to be converted into the number 3, but when we try to subtract it with undefined we get NaN since we are trying to subtract with an undefined number. 
14. 
A. true, This is true since the unicode number is larger than the number 1.
B. false, This is false becaues the unicode number for '2' is larger than '12'.
C. True, since when we use the == it converts the '2' to a number thus making it true that 2 == 2.
D. false, since if we added a third = sign then it will not change the '2' to a number and it will keep it as a string thus comparing the string '2' and 2 which are technically not the same.
E. False, Since we are technically comparing 1 == 2 which is not true. (True = 1)
F. true, since when we use the Boolean() function with a non zero number it will return true so when we use Boolean(2) === true, this statement is true since our first statement will become true thus making the statement true since true === true.
15. the difference between == and === operators is that == is a loose equality operator meaning that if we compare 2 == '2' then it would return true since if we change the type of variable it will be the same. But for === it will not change the type of variable so if we had '2' === 2 it will be false since they do not have the same variable type. 
16. look at part2-question16.js file
17. This will return [2, 4, 6] since we take the array [1, 2, 3] with the doSomething function. then when we run it with the modifyArray function we create a newArr to store the changed array elements. we then get into the for loop and we iterate until we get to the end of the given array. We push the new element into newArr which is gotten by using the callback function which is basically the doSomething function. Within the doSomething function we take the number that is given to use which in this example is the first element of our array and multiply it by 2. Then once that finishes we push that new value into newArr and repeat until the end of the original array. Once finished we return newArr which should have all the new modified elements. 
18. check part2-question18.js
19. 
1
4
3
2