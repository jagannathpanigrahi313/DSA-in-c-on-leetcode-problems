<img width="484" height="302" alt="image" src="https://github.com/user-attachments/assets/cc9066a6-4628-4eb0-be94-31a0f3d86618" />

As you solve more LeetCode problems, always follow this order:
1) Read the problem statement.
2) Read the examples.
3) Read the constraints.
4) Decide what time complexity is likely needed.
5) Then start thinking about the algorithm.
This habit will help you choose the right approach much more quickly

1) Two Sum 
```cpp
class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {

        int n = nums.size();

        for(int i = 0; i < n; i++) {
            for(int j = i + 1; j < n; j++) {

                if(nums[i] + nums[j] == target) {// such that they add up to target
                    return {i, j};
                }
            }
        }

        return {};
    }
};
```
2) 
