# nums.py
<find_missing_nums(nums)>
var array = [1,3,5,6,8,9];

function getFirst(array, n) {
    if (array == null) return false;
    if (n == null) return array[0];
  return array.slice(0, n);
};
<find_missing_nums(nums)>
