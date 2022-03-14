* C++中各种map的使用
  map输入C++中的key-value容器。分别有map/hash_map/unordered_map/vector_map。

  map与unordered_map之间的区别：
	1.  map的有序的， unordered_map是无序的。
	2.  map内部是由一个红黑树实现，该结构具有自动排序的功能，因此map中的元素都是有序的，同时红黑树的效率决定了map的效率。而unordered内部实现了一个哈希表，因此它是无序的。
	3.  map适用于排序问题，unordered适合查找问题。
	4.  #include<map> #include<unorederd_map>
