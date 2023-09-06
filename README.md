[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11754715&assignment_repo_type=AssignmentRepo)
# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```

Answer: The first thing this function does is check if the array length is 1, then it returns the first element, this means that this is the largest element. It then creates a varible that is a new array that includes the entire array minus the first element. If the new variable is greater than the first element, that new varible is returned, otherwise the first element of the array is returned. This function will return the greatest number in an array. 
