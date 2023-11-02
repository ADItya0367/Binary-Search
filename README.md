# Binary-Search

// ITERATIVE
1st Method that we are using here is iterative method
define variables as low , high and mid 
here in tterative method we will calculate the mid and checck if
**mid==target element return mid;
**mid <=target move low=mid+1;
**else mid>=target high=mid-1;

Inside main function 
** Declare the value of array
** calculate the size of the array by sizeof(array)/sizeof(array[0]);
** Call the function and store the value in a variable result now check if result is -1 
** if yes then return element not found 
  else return result;


// RECURSIVE 
In the recursive Method we will define the function and check for every call 
Meaning we will just do the same thing as iterative but instead of checking the value of mid everytime call the function 
** Check the code to understand well
