# codingbat-warmup2-arrayCount9
    public int arrayCount9(int[] nums) {
      int h=0;
      int n=0;
      while(h<nums.length)
      {
        if(nums[h]==9)
        {
          n+=1;
          h+=1;
        }
        else h+=1;
    
    }
    return n;
    }
