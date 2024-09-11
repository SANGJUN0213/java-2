# java-2
function checkEvenOdd(number) {
  if (number % 2 === 0) {
      console.log("짝수입니다");
  } else {
      console.log("홀수입니다");
  }
}

function checkAge(age) {
  if (age >= 18) {
      console.log("성인입니다");
  } else {
      console.log("미성년자입니다");
  }
}

function getDayName(dayNumber) {
  switch (dayNumber) {
      case 1: console.log("월요일"); break;
      case 2: console.log("화요일"); break;
      case 3: console.log("수요일"); break;
      case 4: console.log("목요일"); break;
      case 5: console.log("금요일"); break;
      case 6: console.log("토요일"); break;
      case 7: console.log("일요일"); break;
      default: console.log("잘못된 입력입니다");
  }
}
function printEvenNumbers() {
  for (let i = 1; i <= 100; i++) {
      if (i % 2 === 0) {
          console.log(i);
      }
  }
}

function printNumbers() {
  let i = 5;
  while (i <= 15) {
      console.log(i);
      i++;
  }
}

function inputUntilTen() {
  let input;
  do {
      input = prompt("숫자를 입력하세요:");
      console.log("입력된 숫자: " + input);
  } while (input != 10);
}
function addNumbers(a, b) {
  return a + b;
}
console.log(addNumbers(3, 5));


function multiplyNumbers(a, b, c) {
  return a * b * c;
}
console.log(multiplyNumbers(2, 3, 4));


function greet(name) {
  console.log(`안녕하세요, ${name}님!`);
}
greet("철수");

const subtract = function(a, b) {
  return a - b;
};
console.log(subtract(10, 3));


const sum = function(a, b, c) {
  return a + b + c;
};
console.log(sum(1, 2, 3));

const add = (a, b) => a + b;
console.log(add(4, 7));


const square = (n) => n * n;
console.log(square(5));


const doubleArray = (arr) => arr.map(n => n * 2);
console.log(doubleArray([1, 2, 3, 4]));


const checkAgeArrow = (age) => age >= 18 ? "성인" : "미성년자";
console.log(checkAgeArrow(20));

function findMax(a, b) {
  return a > b ? a : b;
}
console.log(findMax(10, 20));


function grade(score) {
  if (score >= 90) return 'A';
  else if (score >= 80) return 'B';
  else if (score >= 70) return 'C';
  else return 'F';
}
console.log(grade(85));

function getSeason(month) {
  switch (month) {
      case 3: case 4: case 5: console.log("봄"); break;
      case 6: case 7: case 8: console.log("여름"); break;
      case 9: case 10: case 11: console.log("가을"); break;
      case 12: case 1: case 2: console.log("겨울"); break;
      default: console.log("잘못된 월 입력입니다.");
  }
}
getSeason(4);

function sumNumbers() {
  let sum = 0;
  for (let i = 1; i <= 10; i++) {
      sum += i;
  }
  return sum;
}
console.log(sumNumbers());  


function printMultiplesOfThree() {
  let i = 1;
  while (i <= 20) {
      if (i % 3 === 0) {
          console.log(i);
      }
      i++;
  }
}
printMultiplesOfThree(); 
