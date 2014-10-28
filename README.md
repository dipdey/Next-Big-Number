<p>Next-Big-Number<br />
===============</p>

<p>Find next greater number with same set of digits</p>

<p>Algorithm:<br />
1. convert the number to digit array<br />
2. from the last position find first digit which is greater than next (arr[i] > arr[i-1])<br />
3. find the next big decimal from that point (i) to the end<br />
4. swap the (i-1)th number with the next big decimal.<br />
5. qsort the the array from index &quot;i&quot; till end<br />
6. Done</p>
