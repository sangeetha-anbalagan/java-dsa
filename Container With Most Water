//find width,area
//width =last index-first index;
//area=min*width

class Solution {
    public int maxArea(int[] height) {
        int left=0;
        int right=height.length-1;
        int max=0;
        
        while(left<right){
            int width,area;
            int m=Math.min(height[left],height[right]);
            width=right-left;
            area=m*width;
            max=Math.max(max,area);
        
            if(height[left]<height[right]){
                left++;
            }
            else{
                right--;
            }
        }
        return max 
    }
}
