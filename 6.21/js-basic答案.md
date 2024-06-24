```javascript
let x = 2024;

console.log(x); // 输出x
console.log(2 * x); // 输出x的两倍
console.log(x ** 2); // 输出x的平方
console.log(x * x * x); // 输出x的三次方
console.log(x ** 5); // 输出x的五次方
console.log(x + ""); // 输出x的字符串形式
console.log(x >= 50 && x <= 100); // 输出x是否在50到100以内，是输出true，不是输出false
console.log(x % 2 == 1); // 输出x是否为奇数，是输出true，不是输出false
console.log(x % 2 == 0); // 输出x是否为偶数，是输出true，不是输出false
console.log(x > 10 ? "foo" : x < 10 ? "bar" : "baz"); // x大于10输出foo,小于10输出bar,等于10输出baz
console.log(x % 10); // 输出x的个位数
console.log(Math.floor(x / 100) % 10); // 输出x的百位数
console.log(x % 100); // 输出x百位数以下的部分，对于2021，即输出21，对于2035，即输出35
console.log(x > 200 && x % 3 === 0 && x % 7 !== 0); // 输出x是否大于200且为3的倍数但不是7的倍数
console.log(Math.floor((x - 1) / 100) + 1); 方案二:console.log((x - x % 100) / 100 + 1)// 输出x做为年份时，所在的世纪，对于2022即输出21，对于1864即输出19
console.log(x % 4 === 0); // 输出x做为年份时，当年是否会举办奥运会（假设奥运会每四年一届）
console.log(x % 4 === 2); // 输出x做为年份时，当年是否会举办世界杯（假设世界杯每四年一届，从1930年开始）
console.log((x % 4 === 0 && x % 100 !== 0) || x % 400 === 0); // 输出x做为年份时，是否为闰年，是输出true，不是输出false
console.log(isPrime(x)); // 输出x是否为素数（此时x范围为0以上100以内）

function isPrime(num) {
    if (num <= 1) return false;
    if (num <= 3) return true;
    if (num % 2 === 0 || num % 3 === 0) return false;
    for (let i = 5; i * i <= num; i += 6) {
        if (num % i === 0 || num % (i + 2) === 0) return false;
    }
    return true;
}
方案二:console.log(x == 2 || x == 3 || x == 5 ||.....)一共25个都列举出来
