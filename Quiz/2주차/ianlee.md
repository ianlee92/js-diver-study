> π 9μ₯ - νμ λ³ν

```jsx
// λ¬Έμμ΄ νμμΌλ‘ λ³ν
-0 + ''             //
1 + ''              //
-1 + ''             //
null + ''           //
undefined + ''      // 
[] + ''             // 
[10, 20] + ''       // 

// μ«μ νμμΌλ‘ λ³ν
1 - '1'         // 
1 / 'one'       // 
'1' > 0         // 
+''             // 
+'string'       // 
+true           // 
+false          // 
+null           // 
+undefined      // 
+[]             // 
+[10, 20]       // 

// λΆλ¦¬μΈ νμμΌλ‘ λ³ν
!!''        // 
!!true      // 
!!'true'    // 
!!false     // 
!!'false'   // 
!!1         // 
!!0         // 
!!NaN       // 
!!null      // 
!!undefined // 
!!{}        // 
!![]        // 
```

<img src="../icon.png">

β

```jsx
// λ¬Έμμ΄ νμμΌλ‘ λ³ν
-0 + ''             // "0"
1 + ''              // "1"
-1 + ''             // "-1"
null + ''           // "null"
undefined + ''      // "undefined"
[] + ''             // ""
[10, 20] + ''       // "10,20"

// μ«μ νμμΌλ‘ λ³ν
1 - '1'         // 0
1 / 'one'       // NaN
'1' > 0         // true
+''             // 0
+'string'       // NaN
+true           // 1
+false          // 0
+null           // 0
+undefined      // NaN
+[]             // 0
+[10, 20]       // NaN

// λΆλ¦¬μΈ νμμΌλ‘ λ³ν
!!''        // false
!!true      // true
!!'true'    // true
!!false     // false
!!'false'   // true
!!1         // true
!!0         // false
!!NaN       // false
!!null      // false
!!undefined // false
!!{}        // true
!![]        // true
```

* * *

> π 10μ₯ - νλ‘νΌν° μ κ·Όλ°©λ²

```jsx
var person = {
  lastName: 'Lee',
};

console.log(person.lastName); // (1)
console.log(person.age); // (2)
console.log(person[lastName]); // (3)
console.log(person['lastName']); // (4)
console.log(person[age]); // (5)
console.log(person['age']); // (6)

// λ³΄κΈ° 1) Lee 2) undefined 3) ReferenceError: lastName is not defined
```

<img src="../icon.png">

β (1) 1 (2) 2 (3) 3 (4) 1 (5) 3 (6) 2

- νλ‘νΌν°μ μ κ·Όν λ°©λ²μ λ§μΉ¨ν(dot) νλ‘νΌν°μ λκ΄νΈ(bracket) νλ‘νΌν°κ° μλ€. λκ΄νΈ νλ‘νΌν° μ κ·Ό μ°μ°μ λ΄λΆμ μ§μ νλ νλ‘νΌν° ν€λ λ°λμ λ°μ΄νλ‘ κ°μΌ λ¬Έμμ΄μ΄μ΄μΌ νλ€.
- κ°μ²΄μ μ‘΄μ¬νμ§ μλ νλ‘νΌν°μ μ κ·Όνλ©΄ RefrenceErrorκ° λ°μνμ§ μκ³  undefinedλ₯Ό λ°ννλ€.
