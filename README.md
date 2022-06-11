const ar = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

 learn array methods
 1. map
 2. filter
 3. reduce
 4. find
 5. findIndex
 6. some
 7. every
 8. sort
 9. reverse
 10. concat
 11. slice
 12. splice
 13. indexOf
 14. lastIndexOf
 15. includes
 16. join
 17. toString


 1. map
 map is used to transform the elements of an array
 map returns a new array

 const newAr = ar.map(item => item * 2);
 console.log(newAr);
 [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]

 2. filter
 filter is used to filter the elements of an array
 filter returns a new array
 const far = ar.filter(item => item > 5);
 console.log(far);
 [6, 7, 8, 9, 10]

 3. reduce
 reduce is used to reduce the elements of an array
 reduce returns a single value
 const rar = ar.reduce((acc, item) => {
     return acc + item;
 });
 console.log(rar);
 55


 4. find
 find is used to find the first element that satisfies a condition
 find returns the first element that satisfies the condition
 const fr = ar.find(item => item > 5);
 console.log(fr);
 6

 5. findIndex
 findIndex is used to find the index of the first element that satisfies a condition
 findIndex returns the index of the first element that satisfies the condition
 const fi = ar.findIndex(item => item > 5);
 console.log(fi);
 6

 6. some
 some is used to check if at least one element satisfies a condition
 some returns a boolean
 const so = ar.some(item => item > 5);
 console.log(so);

 7. every
 every is used to check if all elements satisfy a condition
 every returns a boolean
 const ea = ar.every(item => item > 0);
 console.log(ea);

 8. sort
 sort is used to sort the elements of an array
 sort returns a new array
 const sor = ar.sort((a, b) => a - b);
 console.log(sor);
 [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

 9. reverse
 reverse is used to reverse the elements of an array
 reverse returns a new array
 const rev = ar.reverse();
 console.log(rev);

 10. concat
 concat is used to concatenate two or more arrays
 concat returns a new array
 const con = ar.concat([1, 2, 3, 4, 5]);
 console.log(con);

 11. slice
 slice is used to extract a part of an array
 slice returns a new array
 slice not mutates the original array
 const sl = ar.slice(3, 6);
 console.log(sl);

 12. splice
 splice is used to remove or add elements from an array
 splice mutates the original array
 splice returns a new array
 const sp = ar.splice(3, 2);
 console.log(sp);

 13. indexOf
 indexOf is used to find the index of an element
 indexOf returns the index of the element
 const ind = ar.indexOf(5);
 console.log(ind);

 14. lastIndexOf
 lastIndexOf is used to find the last index of an element
 lastIndexOf returns the last index of the element
 const lind = ar.lastIndexOf(5);
 console.log(lind);

 15. includes
 includes is used to check if an array includes an element
 includes returns a boolean
 const inl = ar.includes(5);
 console.log(inl);

 16. join
 join is used to join the elements of an array into a string
 join returns a string
 const jo = ar.join('-');
 console.log(jo);
 1-2-3-4-5-6-7-8-9-10

 17. toString
 toString is used to convert an array into a string
 toString returns a string
 const to = ar.toString();
 console.log(to);
 1,2,3,4,5,6,7,8,9,10

 18. forEach
 forEach is used to iterate over an array
 forEach does not return a value
 const forEach = ar.forEach(item => {
     console.log(item);
 }
 );
 console.log(forEach);
 undefined
