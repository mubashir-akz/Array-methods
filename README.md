### const ar = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

# Array methods
 ## 1. [Map](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#1-map)
 ## 2. [Filter](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#2-filter-1)
 ## 3. [Reduce](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#3-reduce-1)
 ## 4. [Find](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#4-find-1)
 ## 5. [Findindex](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#5-findindex-1)
 ## 6. [Some](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#6-some-1)
 ## 7. [Every](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#7-every-1)
 ## 8. [Sort](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#8-sort-1)
 ## 9. [Reverse](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#9-reverse-1)
 ## 10. [Concat](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#10-concat-1)
 ## 11. [Slice](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#11-slice-1)
 ## 12. [Splice](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#12-splice-1)
 ## 13. [IndexOf](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#13-indexof-1)
 ## 14. [LastIndexOf](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#14-lastIndexOf-1)
 ## 15. [includes](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#15-includes-1)
 ## 16. [join](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#16-join-1)
 ## 17. [toString](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#17-toString-1)
 ## 18. [forEach](https://github.com/mubashir-akz/Array-methods/edit/main/README.md#18-forEach-1)

### 1. map
 map is used to transform the elements of an array
 map returns a new array
``` javascript
 const newAr = ar.map(item => item * 2);
 console.log(newAr);
  [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
 ```

 ### 2. filter
 filter is used to filter the elements of an array
 filter returns a new array
 ```javascript
 const far = ar.filter(item => item > 5);
 console.log(far);
 [6, 7, 8, 9, 10]
 ```


 ### 3. reduce
 reduce is used to reduce the elements of an array
 reduce returns a single value
 ```javascript
 const rar = ar.reduce((acc, item) => {
     return acc + item;
 });
 console.log(rar);
 ```

 55


 ### 4. find
 find is used to find the first element that satisfies a condition
 find returns the first element that satisfies the condition
 ```javascript
 const fr = ar.find(item => item > 5);
 console.log(fr);
 ```
 6

 ### 5. findIndex
 findIndex is used to find the index of the first element that satisfies a condition
 findIndex returns the index of the first element that satisfies the condition
 ```javascript
 const fi = ar.findIndex(item => item > 5);
 console.log(fi);
 ```
 6

 ### 6. some
 some is used to check if at least one element satisfies a condition
 some returns a boolean
 ```javascript
 const so = ar.some(item => item > 5);
 console.log(so);
 ```

 ### 7. every
 every is used to check if all elements satisfy a condition
 every returns a boolean
 ```javascript
 const ea = ar.every(item => item > 0);
 console.log(ea);
 ```

 8. sort
 sort is used to sort the elements of an array
 sort returns a new array
 ```javascript
 const sor = ar.sort((a, b) => a - b);
 console.log(sor);
 [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
 ```

 ### 9. reverse
 reverse is used to reverse the elements of an array
 reverse returns a new array
 ```javascript
 const rev = ar.reverse();
 console.log(rev);
 ```

 ### 10. concat
 concat is used to concatenate two or more arrays
 concat returns a new array
 ```javascript
 const con = ar.concat([1, 2, 3, 4, 5]);
 console.log(con);
 ```

 ### 11. slice
 slice is used to extract a part of an array
 slice returns a new array
 slice not mutates the original array
 ```javascript
 const sl = ar.slice(3, 6);
 console.log(sl);
 ```

 ### 12. splice
 splice is used to remove or add elements from an array
 splice mutates the original array
 splice returns a new array
 ```javascript
 const sp = ar.splice(3, 2);
 console.log(sp);
 ```

 ### 13. indexOf
 indexOf is used to find the index of an element
 indexOf returns the index of the element
 ```javascript
 const ind = ar.indexOf(5);
 console.log(ind);
 ```

 ### 14. lastIndexOf
 lastIndexOf is used to find the last index of an element
 lastIndexOf returns the last index of the element
 ```javascript
 const lind = ar.lastIndexOf(5);
 console.log(lind);
 ```

 ### 15. includes
 includes is used to check if an array includes an element
 includes returns a boolean
 ```javascript
 const inl = ar.includes(5);
 console.log(inl);
 ```

 ### 16. join
 join is used to join the elements of an array into a string
 join returns a string
 ```javascript
 const jo = ar.join('-');
 console.log(jo);
 // 1-2-3-4-5-6-7-8-9-10
 ```

 ### 17. toString
 toString is used to convert an array into a string
 toString returns a string
 ```javascript
 const to = ar.toString();
 console.log(to);
 // 1,2,3,4,5,6,7,8,9,10
 ```

 ### 18. forEach
 forEach is used to iterate over an array
 forEach does not return a value
 ```javascript
 const forEach = ar.forEach(item => {
     console.log(item);
 }
 );
 console.log(forEach);
// undefined
 ```

