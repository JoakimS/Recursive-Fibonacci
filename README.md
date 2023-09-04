# Recursive-Fibonacci
The common mistake is counting sequences not N
function alpha(n){
if (n<=1){
return n
}
else{
return alpha(n-1) + alpha(n-3);
}
}
console.log(alpha(10));
