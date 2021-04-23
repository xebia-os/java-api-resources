# Basic Problems

1. Write a Java function that takes a positive integer greater than 0 and generate a sequence that follow rules:

  * If the current number is even then it divides by two else if is odd it multiplies by three and add one
  * It stops if number is 1

```
For example, if I give number 3 then I should get [10, 5, 16, 8, 4, 2, 1] 

When number is 4 I get [2,1]

When number is 7 I get [22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]
```

------

2. Implement a LRU cache (using a LinkedHashMap). The cache should be generic with strong type safety

------

3. A police station has an alerting system with 3 priority levels:

- CRITICAL - homicide, gang war, terror attack

- URGENT - violence, VIP cavalcade

- NORMAL - theft, kidnapping

  Implement a system using a PriorityQueue to alert available officers of any incidents being reported to the station - they should be addressed on a priority basis irrespective of the order the incidents were reported in.

------

5. Implement `ImmutableDate` that is built on top of Date.  The `ImmutableDate` need to have following contract

   ```java
   public class ImmutableDate {
     public ImmutableDate(Date date){}
     public ImmutableDate addYears(int yearsToAdd);
     public ImmutableDate addMonths(int monthsToAdd);
     public ImmutableDate addDays(int daysToAdd);
   }
   ```

------

6. Jump Game

Given an array of non-negative integers, you are initially positioned at the first index of the array.

Each element in the array represents your maximum jump length at that position.

Determine if you are able to reach the last index.

*Example 1*:

Input: [2,3,1,1,4]
Output: true
Explanation: Jump 1 step from index 0 to 1, then 3 steps to the last index.

*Example 2*:

Input: [3,2,1,0,4]
Output: false
Explanation: You will always arrive at index 3 no matter what. Its maximum
             jump length is 0, which makes it impossible to reach the last index.


// Copy this and create your own class 

    class JumpGame {
      public boolean canJump(int[] nums) {
      }
    }

------

7. Search in Rotated Sorted Array

Suppose an array sorted in ascending order is rotated at some pivot unknown to you beforehand (i.e., [0,1,2,4,5,6,7] might become [4,5,6,7,0,1,2]).

You are given a target value to search. If found in the array return its index, otherwise return -1.

You may assume no duplicate exists in the array.

Your algorithm's runtime complexity must be in the order of _O_(log _n_).

*Example* 1:

Input: nums = [

4,5,6,7,0,1,2], target = 0
Output: 4

*Example* 2:

Input: nums = [

4,5,6,7,0,1,2], target = 3

Output: -1

// Copy this and create your own class

```
class SearchRotated {
  public int search(int[] nums, int target) {
  }
}
```

------

8. 3 Sum

Given an array nums of n integers, are there elements a, b, c in nums such that a + b + c = 0? Find all unique triplets in the array which gives the sum of zero.

Note:

The solution set must not contain duplicate triplets.

*Example*:

Given array nums = [-1, 0, 1, 2, -1, -4],

A solution set is:

[

  [-1, 0, 1],

  [-1, -1, 2]

]

```
class ThreeSum {

    public List<List<Integer>> threeSum(int[] nums) {
    }
}
```

------

9. Container With Most Water

Given _n_ non-negative integers _a1_, _a2_, ..., an , where each represents a point at coordinate (_i_, _ai_). _n_ vertical lines are drawn such that the two endpoints of line _i_ is at (_i_, _ai_) and (_i_, 0). Find two lines, which together with x-axis forms a container, such that the container contains the most water.

Note: You may not slant the container and _n_ is at least 2.

![Image](./image/question_1.jpg)

The above vertical lines are represented by array [1,8,6,2,5,4,8,3,7]. In this case, the max area of water (blue section) the container can contain is 49.  

*Example*:

Input: [1,8,6,2,5,4,8,3,7]

Output: 49

// Copy this and create your own class

```
class WaterInContainer {
    public int maxArea(int[] height) {

    }
}
```

