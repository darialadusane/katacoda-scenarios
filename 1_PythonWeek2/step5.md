Messy Terminal? `clear`{{execute}} it.
<hr>

Lists can grow to any length you wish them to be (have as many elements as you want), can be added to at any point and any element can be changed at any point in time, as you saw earlier in this session. Methods for adding elements to a list are important to know as you will be using them regulalry. Below we will explore some different methods you can use to do so.

</br>

## **Append**
The append method is the default method most people use when adding an element to a list. It is simple and easy to understand and quite efficient, as it just adds the element to the end of the list and increases the lists length by one, as shown below:

<pre class="file" data-filename="append.py" data-target="replace">
names = ["Ellie", "Dan", "Perry", "Justin"]
names.append("Max")
print(names)
print(len(names))
</pre>

Copy the code above over to the editor and then press
`python append.py`{{execute}}

When you run the code you should see that the variable "Max" has now been added to the end of the list and the list length is now 5.

</br>

## **Insert**
The insert method allows you to state where in the list you would like the new element to be placed, by providing the method with an index. For this example the names list has already been sorted and we assume that the program knows the name "Max" fits between "Justin" and "Perry" in alphabetical order:

<pre class="file" data-filename="insert.py" data-target="replace">
sorted_names = ["Dan", "Ellie", "Justin", "Perry"]
sorted_names.insert(3, "Max")
print(sorted_names)
</pre>

Copy the code above over to the editor and then press
`python insert.py`{{execute}}

As you can see the insert method is provided two arguments, the index which it has to insert the element before and the element it is inserting. 

When you run the code you should be able to see that the element "Max" has been inserted in the list between "Justin" and "Perry" as expected. This method also increases the length of the list just as the previous did, since we are adding another element.

</br>

## **Extend**
This final method extends the list by adding multiple elements to it, it does this by basically merging another list into the existing one, by adding each of the new lists elements to the existing list. The length of the list is increased by however many elements were added. The list being added can be of a different Data Type (different variable type) as the current one and it will still work. Below is an example of the extend method being used:

<pre class="file" data-filename="extend.py" data-target="replace">
names = ["Ellie", "Dan", "Perry", "Justin"]
numbers = [10, 90, 23, 46, -20]
names.extend(numbers)
print(names)
</pre>

Copy the code above over to the editor and then press
`python extend.py`{{execute}}

As you can see all the numbers list elements are added to the end of the names list and the length of the list is increased to 9.