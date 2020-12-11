def countPairs(nums):
    count = 0

    while len(nums):
        probe = nums[0]
        count += pairs(len([x for x in nums if x == probe]))
        nums = [x for x in nums if x != probe]

    return count
