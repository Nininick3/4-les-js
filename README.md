/*
let arr = [true, false, 1, "LoL", "LmaO"];
alert (arr);
*/
/*
let a = prompt('a = ');
let b = prompt('b = ');
function P(a) {
    return a*4;
};

function S(a, b) {
    return a * b;
};

let q = prompt('S or P');
 if (q == 'P') {
    alert(P(a))
 }else if (q == 'S') {
    alert(S(a, b))
};
*/
/*
function cube(num) {
    function square() {
        return num*num;
    }
    return square()*num
}

let number = prompt('Enter number');
alert('number ** 3' + cube(number));
*/

let name = prompt('Enter your name - ');
let surname1 = prompt('Enter your surname1 - ');
let surname2 = prompt('Enter your surname2 - ');
function fio(name, surname1, surname2) {
    return `${name} ${surname1} ${surname2}`;
}

alert(fio(name, surname1, surname2))
