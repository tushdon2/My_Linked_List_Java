# [myDoublyLinkedList.java](../myDoublyLinkedList.java)

This file contains the class ```myDoublyLinkedList```. A Doubly linked List can be made by creating an object of this class as:

```myDoublyLinkedList<E> object = new myDoublyLinkedList<>();``` where E is data type of the objects to be stored in the Linked List.

E.g. ```E``` can be ```Integer``` for creating a Linked List to store integers.

The Linked List follows zero based indexing.

Implementation can be found in the ```main``` method of ```runner``` class in the [runner.java](https://github.com/tushdon2/My_Linked_List_Java/blob/84b250038fd73b9913a7afd6c4066bb8514c2dae/runner.java#L66) file.

The properties of its members are similar to the properties of members of [```mySinglyLinkedList```](../mySinglyLinkedList.java) class, except:
* #### ```Node```
  Apart from what is described in [mySinglyLinkedList.md](https://github.com/tushdon2/My_Linked_List_Java/blob/84b250038fd73b9913a7afd6c4066bb8514c2dae/README/mySinglyLinkedList.md#node), it contains:
    * ##### ```prev```
      It is an object of type ```Node``` and points to the previous node (if the current node is the first node it will point to ```null```).
