class Solution:
    def intersection(self, nums1: List[int], nums2: List[int]) -> List[int]:
        # take a look at numbers in the first list, create a hashset to remove duplicates
        numslist_1 = set(nums1)
        # create an empty list which will be used to store the number in the intersection
        result = []

        for _ in nums2:
            if _ in numslist_1:
                result.append(_)
                numslist_1.remove(_)
        return result
