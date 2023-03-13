# Oleg Aroyan | Frontend developer

|that's me|contacts|
|---|---|
|![MyPhoto](https://i.ibb.co/5Fm1tFL/oleg.jpg) |📫skipemyspace@gmail.com<br>📱@olegaroyan<br>📍Bangkok, Thailand|

I want to build my career in the sphere of **Frontend** \
and to create modern and user-friendly websites and apps.

## Skills

|Name|Level|
|---|---|
|`HTML` | 🤩🤩🤩🤩🤩|
|`CSS`  | 🤩🤩🤩🤩🤩|
|`Javascript`|😐😐😐|
|`C` |🙂🙂🙂🙂| 
|`Git` | 🙂🙂🙂🙂|
|`Figma` | 🙂🙂🙂🙂|
|`Photoshop` | 🤩🤩🤩🤩🤩|

## Projects
- [JavaScript Calculator](https://github.com/olegpreed/JavaScript-Calculator)
- [Website prototypes](https://www.frontendmentor.io/profile/olegpreed)
- [Website designs](https://disk.yandex.com/d/04zN-5Pv347QkQ)
- [2D game](https://github.com/olegpreed/so_long)

## Education

|Name|Qualification|Years|
|---|---|---|
|School 42|Programmer|2021 - Present|
|Moscow State University|English teacher|2019 - 2021|

## Certificates
`TKT (Teaching Knowledge Test)`
`SKILLBOX webdesign courses`

## Languages
`English(C2)`
`Spanish(B1)`
`Russian(Native)`

## Code
Codewars challange «Does my number look big in this?»
<table>
  <tr>
    <td><details><summary>Task</summary>
A Narcissistic Number (or Armstrong Number) is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base. In this Kata, we will restrict ourselves to decimal (base 10).

For example, take 153 (3 digits), which is narcissistic:

    1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153
and 1652 (4 digits), which isn't:

    1^4 + 6^4 + 5^4 + 2^4 = 1 + 1296 + 625 + 16 = 1938
The Challenge:

Your code must return true or false (not 'true' and 'false') depending upon whether the given number is a Narcissistic number in base 10.

This may be True and False in your language, e.g. PHP.

Error checking for text strings or other invalid inputs is not required, only valid positive non-zero integers will be passed into the function.
</details></td>
    <td><details><summary>My solution</summary>
      
```javascript
function narcissistic(value) {
  let copy = value;
  let sum = 0;
  let power = 1;
  let powerConst;

  while (copy >= 10) {
    copy = copy / 10;
    power++;
  };
  powerConst = power;
  while (power >= 1) {
    copy = Math.floor(value / (10 ** (power - 1))) % 10;
    sum += copy ** powerConst;
    power--;
  }
  if (sum == value) return true;
  else return false;
}
```
      
</details></td>
  </tr>
</table>
