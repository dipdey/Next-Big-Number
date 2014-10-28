<p>Next-Big-Number ===============</p>

<p>Find next greater number with same set of digits</p>

<p>Algorithm: 1. convert the number to digit array 2. from the last position find first digit which is greater than next (arr[i] > arr[i-1]) 3. find the next big decimal from that point (i) to the end 4. swap the (i-1)th number with the next big decimal. 5. qsort the the array from index &quot;i&quot; till end 6. Done</p>
