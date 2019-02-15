# JavaScript array starts from index 1?
~~~
false
started zero 
~~~

# Fill in the blank with correct option if we want to print the entire array:
~~~

arr = [1,2,3,4]
​
for(var i=0;i<(____);i++)
  console.log(arr[i])

1 len(arr)
2 size(arr)
3 arr.size()
 4 arr.length(ans)
~~~
#3 What will be the output of the following fragment of code?
~~~
arr = [1,2,3,4]
arr[4]

1 4
2 error
3 0
4 undefined(ans)

~~~

#Array elements are stored in sequential or random memory locations?
~~~
1 Sequential
2 Random
3 Both A and B
4 None of the above(ans)
~~~
# 5What will be the output of following piece of code?
~~~
function foo(value, arr){
    value = 1
    arr[0] = 44
}
var v = 3
var arr = [1, 2, 3]
foo(v, arr)
console.log(v, arr[0])

1 1 44
2 3 44(ans)
3 3 1
4 1 1
~~~
# 6 What will be output of following piece of code?
~~~
var arr = [[[1, 2], [3, 4]], [[5, 6], [7, 8]]]
function foo(m){
  var v = m[0][0];
  for(let row of m){
    for(let element of row){
      if( v < element)
        v = element
    }
  }
  return v
}

console.log(foo(arr[0]))

1   1

2   2

3   3

4   4(ans)

~~~
# 7 What will be the output of following piece of code?
~~~
var arr = [1, 2, 3, 4, 5, 6]
for(var i=1;i<6;i++)
    arr[i - 1] = arr[i]
for(var i=0;i<6;i++)
    console.log(arr[i])
1 123456
2 234566(ans)
3 234561
4 112345

~~~

# 8 What is the output of the following piece of code?
~~~
var values=[];
function f(i, values){
    values.push(i)
    console.log(values)
    return values
}
f(1,values)
f(2,values)
f(3,values)

1 [1] [1, 2] [1, 2, 3](ans)


2 [1] [2] [3]

3 [1, 2, 3]

4 1 2 3

~~~

# 9 What is the output of the following piece of code?
~~~
arr = [[1, 2, 3, 4],
       [4, 5, 6, 7],
       [8, 9, 10, 11],
       [12, 13, 14, 15]]
for(var i=0;i<4;i++)
    console.log(arr[i].pop())

1  1 2 3 4

2  1 4 8 12

3  12,13,14,15

4  4 7 11 15(ans)
~~~

#10 
Which of the following is true about JavaScript arrays?
~~~
 1 Arrays can contain elements of different types.(ans)

 2 Arrays are stored sequentially in memory.

 3 Arrays can only be used to perform complex mathematical calculations.

 4 Arrays are un-ordered collections.

 ~~~

 











