//n,n+1,n+2,n+3......
//if index value<current value==add curent value+index value;
//if index value>current value==index value;
//if current value>max
//max=current

class Solution {
    public int maxSubArray(int[] nums) {
        int current=nums[0];
        int max=nums[0];
        for(int i=1;i<nums.length;i++){
            int temp=current+nums[i];
            if(temp>nums[i]){
                current=temp;
            }
            else{
                current=nums[i];
            }
            if(current>max){
                max=current;
            }
        }
        return max;  
    }
}
