# Binary Tree

Group:
Ali, Danny, Martin and Dogan

To run the project, start use "stack ghci" on the directory of the project.
Hereafter you use the :r command to compile and load the Main.hs.
You can then use the functions in the main.hs file using the following commnads:
1.  You can populate the tree using the "put" command. An example hereof is populating
    the tree using a list, and the built in fold function as such:
    "listToInsert = foldl put Nil"
    "let a = [2, 7, 17, 21, 34, 39, 42, 55, 63, 79, 84]"
    "let tree = listToInsert a"
    Further inserting data can be done by using the put command as such:
    "let tree2 = put tree 37"
2.  You can then search the tree for a specific value, checking if the tree contains the value
    by using the "find" command. An example hereof is checking if the list contains "34" as such:
    "find tree2 34"
    This will return "True" if the tree contains the value, and "False" if not.
3.  Lastly you can use the "traversing" command to traverse the tree.
    Its as simple as:
    "traversal tree2"
