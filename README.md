# to-return-the-first-element-of-an-array


var first=function(array,n){
    if(array==null)
    return void 0;
    if(n == null)
    return array[0];
    if (n<0)
    return [];
    return array.slice(0,n);
}
console.log(first([1,2,3,4]));
console.log(first([-4,-98,67]))
console.log(first([],34,45));
