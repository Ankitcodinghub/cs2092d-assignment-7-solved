# cs2092d-assignment-7-solved
**TO GET THIS SOLUTION VISIT:** [CS2092D Assignment 7 Solved](https://www.ankitcodinghub.com/product/cs2092d-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95785&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2092D Assignment 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
QUESTIONS

</div>
</div>
<div class="layoutArea">
<div class="column">
1. The Binary Search Tree (BST) data structure supports many of the dynamic-set operations. A BST is organized as a binary tree in which each node is an object that contains a key value. In addition to a key and satellite data, each node contains attributes left, right, and p that point to the nodes corresponding to its left child, its right child, and its parent, respectively. If a child or the parent is missing, the appropriate attribute contains the value NIL. The root node is the only node in the tree whose parent is NIL. The keys in a binary search tree are always stored in such a way as to satisfy the binary-search-tree property:

• Letxbeanodeinabinarysearchtree. Ifyisanodeintheleftsubtreeofx,theny.key≤ x.key. If y is a node in the right subtree of x, then y.key ≥ x.key.

Write a program to create a Binary Search Tree T with distinct keys (with values in the range [1,106]) and perform the operations insertion, deletion, search, successor, predecessor and traversals(inorder, preorder and postorder) on T. Input should be read from console and output should be shown in console. Your program should include the following functions.

<ul>
<li>Main() – creates the Binary Search Tree T with T as the root node (which is NIL initially) and repeatedly reads a character ‘a’, ‘d’, ‘s’, ‘c’, ‘r’, ‘i’, ‘p’, ‘t’, or ‘e’ from the console and calls the sub-functions appropriately until character ‘e’ is entered.</li>
<li>CreateNode(k) creates a new node with key value k and returns a pointer to the new node. All the pointer attributes of the new node are set to NIL.</li>
<li>Insert(T,x) – inserts the node x into the BST T.

Note: The caller of this function is assumed to create the node x using the CreateNode() function.</li>
<li>Delete(T,x) – deletes the node x from the BST T.

Note: The caller of this function is assumed to invoke Search() function to locate the node x.</li>
<li>Search(T,k) – searches for a node with key k in T, and returns a pointer to a node with key k if one exists; otherwise, it returns NIL.</li>
<li>Successor(T,x) – finds the soccessor of the node x in the BST T and prints the data in the successor node.</li>
<li>predecessor(T,x) – finds the predecessor of the node x in the BST T and prints the data in the predecessor node.</li>
<li>Inorder(T) – performs recursive inorder traversal of the BST T and prints the data in the nodes of T in inorder.</li>
<li>Preorder(T) performs recursive preorder traversal of the BST T and prints the data in the nodes of T in preorder.</li>
<li>Postorder(T) performs recursive postorder traversal of the BST T and prints the data in the nodes of T in postorder.
Input format:
</li>
</ul>
<ul>
<li>Each line contains a character from ‘a’, ‘d’, ‘s’, ‘c’, ‘r’, ‘i’, ‘p’, ‘t’, or ‘e’ followed by at most one integer. The integers, if given, are in the range [1,106].</li>
<li>Character ‘a’ is followed by an integer separated by space. In this operation, a node with this integer as key is created and inserted into T by calling the function INSERT().</li>
<li>Character ‘d’ is followed by an integer separated by space. In this operation, the node with this integer as key is deleted from T and the deleted node’s key is printed calling the function DELETE().</li>
<li>Character ‘s’ is followed by an integer separated by space. This operation is to find the node with this integer as key in T by calling the function SEARCH().</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>Character ‘c’ is followed by an integer separated by space. This operation is to find successor of the node with this integer as key in T by calling the function SUCCESSOR().</li>
<li>Character ‘r’ is followed by an integer separated by space. This operation is to find predecessor of the node with this integer as key in T by calling the function PREDECESSOR().</li>
<li>Character ‘i’ is to perform inorder traversal of T by calling the function INORDER().</li>
<li>Character ‘p’ is to perform preorder traversal of T by calling the function PREORDER().</li>
<li>Character ‘t’ is to perform postorder traversal of T by calling the function POSTORDER()</li>
<li>Character ‘e’ is to ‘exit’ from the program.
Output Format:
</li>
</ul>
<ul>
<li>The output (if any) of each command should be printed on a separate line.</li>
<li>For option ‘d’, print the deleted node’s key. If a node with the input key is not present in T,
then print -1.
</li>
<li>For option ‘s’, if the key is present in T , then print 1. If key is not present in T, then print -1.</li>
<li>For option ‘c’, if the successor is present in T, then print the data in the successor node. If successor is not present in T, then print -1.</li>
<li>For option ‘r’, if the predecessor is present in T, then print the data in the predecessor node. If predecessor is not present in T, then print -1.</li>
<li>For option ‘i’, print the data in the nodes of T obtained from inorder traversal.</li>
<li>For option ‘p’, print the data in the nodes of T obtained from preorder traversal.</li>
<li>For option ‘t’, print the data in the nodes of T obtained from postorder traversal.
Sample Input :

a 25 a 13 a 50 a 45 a 55 a 18 c 25 c 55 r 45 r 13 i

p

t

s 10 s 25 d 55 d 13 d 10 d 25 i

s 25 e

Sample Output :

45

-1

25

-1

13 18 25 45 50 55
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
25 13 18 50 45 55 18 13 45 55 50 25 -1

1

55

13

-1

25

18 45 50 -1

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
