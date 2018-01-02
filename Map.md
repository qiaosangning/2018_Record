<table>
<tr>
<td></td>
<td>
HashMap
</td>
<td>
HashTable deprecated
</td>
<td>
ConcurrentMap
</td>
<td>
TreeMap red-black tree
</td>
</tr>
<tr>
<td>
Thread Safe
</td>
<td>
No
</td>
<td>
Yes
</td>
<td>
Yes
</td>
<td>
No
</td>
</tr>
  <tr><td>key==NULL</td><td>Yes</td><td>No</td><td>No</td><td>No</td></tr>
  <tr><td>value==NULL</td><td>Yes</td><td>No</td><td>No</td><td>Yes</td></tr>

</table>

HashTable 是整个对象加锁<br/>
ConcurrentMap 是将对象分为若干个hashmap，然后分区块加锁
