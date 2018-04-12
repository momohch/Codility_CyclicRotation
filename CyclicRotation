// you can write to stdout for debugging purposes, e.g.
// console.log('this is a debug message');

function solution(A, K) {
    // write your code in JavaScript (Node.js 8.9.4)
    var l = A.length - 1; 
    for (var i = 0; i < K; i++){
        var a = A[l];
        for (var j = 0; j < l; j++){
            A[l-j] = A[l-j-1];
        }
        A[0] = a;
    }
    return A;
}
