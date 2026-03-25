class Solution {
    private void reverse(int l, int r, int[] nums){
        int temp;
        while(l<r){
            temp=nums[l];
            nums[l]=nums[r];
            nums[r]=temp;
            l++;
            r--;
        }
    }
    public void rotate(int[] nums, int k) {
        int n=nums.length;
        k=k%n;
        reverse(0,n-1,nums);
        reverse(0,k-1,nums);
        reverse(k,n-1,nums);
    }
}
