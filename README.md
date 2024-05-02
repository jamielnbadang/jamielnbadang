function strCount (str , letter) {
  let count = 0 
  for (let x = 0; x < str.length; x++){
    if (str[x] == letter) {
      count ++; 
    }
  }
   return count;
}
console.log(strCount("Hello", 'o'));
console.log(strCount("Hello", 'l'));
console.log(strCount(" ", 'z'));
