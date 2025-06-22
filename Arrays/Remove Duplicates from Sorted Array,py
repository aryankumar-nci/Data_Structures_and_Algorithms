'''
https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/


26. Remove Duplicates from Sorted Array

'''

class Solution:
    def removeDuplicates(self, nums: List[int]) -> int:
        
        if len(nums)==0:
            return 0

        p=0
        q=0

        for q in range (len(nums)):
            if nums[q]!=nums[p]:
                p= p+1
                nums[p]=nums[q]
        return p+1
        