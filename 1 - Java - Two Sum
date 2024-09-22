class Solution {
    public int[] twoSum(int[] nums, int target) {
        
        Map<Integer, Integer> numMap = new HashMap<>();
        int len = nums.length;

        for (int i = 0; i < len; i++) {
            numMap.put(nums[i], i);
        }

        for (int i = 0; i < len; i++) {
            int comp = target - nums[i];
            if (numMap.containsKey(comp) && numMap.get(comp) != i) {
                int[] answer = {i, numMap.get(comp)};
                return answer;
            }
        }
    return null;
    }
}
