Download Link: https://assignmentchef.com/product/solved-datastructure-assignment-3
<br>






Chapter 3

10 points

<ol>

 <li>Linked lists and arrays:</li>

 <li>What are some advantages of linked lists versus arrays?</li>

 <li>What are some advantages of arrays versus linked lists?</li>

</ol>

15 points

<ol start="2">

 <li>What is the Big-O running time of the following code fragment? Assume lst1 has N items, and lst2 is initially empty.</li>

</ol>

public static void add( List&lt;Integer&gt; lst1, List&lt;Integer&gt; lst2)

{

for ( Integer x : lst1 )

lst2.add(0, x);        // add to front

}

<ol start="2">

 <li>If an ArrayList is passed for lst1 and lst2. Explain your answer.</li>

 <li>If a LinkedList is passed for lst1 and lst2. Explain your answer.</li>

</ol>

15 points

<ol start="3">

 <li>What is the Big-O running time of the following code fragment?</li>

</ol>

public static void erase( List&lt;Integer&gt; lst )

{

Iterator&lt;Integer&gt; itr = lst.iterator();

while ( itr.hasNext() )

{

Integer x = itr.next();          itr.remove();       }

}

<ol>

 <li>If an ArrayList is passed for lst. Explain your answer.</li>

 <li>If a LinkedList is passed for lst. Explain your answer.</li>

</ol>

15 points

<ol start="4">

 <li>What is the Big-O running time of the following code fragment? Assume lst1 has N items, and lst2 has N items.</li>

</ol>

public static int Count( List&lt;Integer&gt; lst1, List&lt;Integer&gt; lst2)

{

Iterator&lt;Integer&gt; itr1 = lst1.iterator();

int count=0;

while ( itr1.hasNext() )

{

Integer x = itr1.next();

Iterator&lt;Integer&gt; itr2 = lst2.iterator();

while ( itr2.hasNext() )

if ( x.equals( itr2.next()) )                count++;

}

return count;

}

<ol start="2">

 <li>If an ArrayList is passed for lst1 and lst2. Explain your answer.</li>

 <li>If a LinkedList is passed for lst1 and lst2. Explain your answer.</li>

</ol>

15 points

<ol start="5">

 <li>What is the Big-O running time of the following code fragment?</li>

</ol>

public static int calc( List&lt;Integer&gt; lst )

{

int count = 0;          int N = lst.size();

for ( int i=0; i&lt;N; i++)

{

if (lst.get(i) &gt; 0)                sum += lst.get(i);             else

sum += lst.get(i) * lst.get(i);

}

return sum;

}

<ol>

 <li>If an ArrayList is passed for lst. Explain your answer.</li>

 <li>If a LinkedList is passed for lst. Explain your answer.</li>

</ol>

15 points

<ol start="6">

 <li>Suppose a Java method receives a List&lt;Integer&gt; and reverses the order of the items it contains by removing each item from the front of the list and pushing it onto a Stack&lt;Integer&gt;, and then popping the items from the stack and inserting each item to the end of the list.</li>

</ol>

What is the expected Big-O running time if:

<ol>

 <li>If an ArrayList is passed. Explain your answer.</li>

 <li>If a LinkedList is passed. Explain your answer.</li>

</ol>

15 points

<ol start="7">

 <li>Show each step of converting a+b*c+(d-e) from infix to postfix notation, using the algorithm described in the textbook that uses a stack.</li>

</ol>

Submit to eLearning:     hw3.doc (.doc can be .txt, .jpg, etc.)