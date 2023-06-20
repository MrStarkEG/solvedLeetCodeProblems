class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:

        sol = []
        for i in range(len(nums)): 
            for j in range(1,len(nums)):
               if nums[i] + nums[j] == target:
                   if i in sol or j in sol or i == j:
                       continue
                   else:
                        sol.append(i)
                        sol.append(j)
        return sol
        
   // gotta work on memory-efficiency
