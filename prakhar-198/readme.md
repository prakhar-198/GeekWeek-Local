NAME-PRAKHAR CHAKRAVARTY
REDG.NO:-20BCE10271



I'm Prakhar Chakravarty Btech 2nd Year student Studying from VIT Bhopal university. I'm a coding enthusiast and working on my skillset associated to coding.
 HERE ARE MY CODES I DID TODAY
 //LARGEST ELEMENT IN AN ARRAY
class Compute {
    
    public long largest(long arr[], long n)
    {
long max=arr[0];
       for(int i=1;i<n;i++){
           if(max<arr[i]){
               max=arr[i];
           }
       }return max;
    }
}
//COUNT THE ZEROS
class Solution {
    int countZeroes(int[] arr, int n) {
        // code here
        int count=0;
        for(int i=0;i<n;i++){
            if(arr[i]==0){
                count++;
            }
        }return count;
    }

}
//Product of maximum in first array and minimum in second
class Complete{
    
    // Function for finding maximum and value pair
    public static long find_multiplication (int arr[], int brr[], int n, int m) {
        long max=arr[0];
       long  min=brr[0];
        for(int i=0;i<n;i++){
            if(max<arr[i]){
                max=arr[i];
            }
            
        }for(int j=0;j<m;j++){
            if(min>brr[j]){
                min=brr[j];
            }
            
        }long product=max*min;return product;
    }
    
    
}
