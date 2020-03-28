/*----------------------------------------------------------------
  --------------------------Made by Énio--------------------------
  -----------------------Last change 28/3/20----------------------*/

Important notes about the heap

Chosing between heapMax and heapMin;

HeapMax --> To use an HeapMax comment line 9 and uncomment line 12

HeapMin --> To use an heapMin comment line 12 and uncomment line 9


Note about vert: The vert is suposed to be the index of you object!!!


Changing the values on the heap;

if you are using heapMax:
  - If you are DECREASING do:
	changeValue(heap, vert, new key);
	sortDown(heap, vert);

  - If you are INCREASING do:
	changeValue(heap, vert, new key);
	sortUp(heap, vert);

If you are using heapMin:
  -If you are DEACREASING do:
	changeValue(heap, vert, new key);
	sortUp(heap, vert);

  - If you are INCREASING do:
	changeValue(heap, vert, new key);
	sortDown(heap, vert);

