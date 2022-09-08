[RssScool-CV]()
## Ashot Bahiran
#####_Web Developer_
___
##### Contact
**Phone** +48 505 643 923
**Email** torgregion1@gmail.com
[LinkedIn](https://www.linkedin.com/in/ashot-bahiran-3a1ab022b/)
[GitHub](https://github.com/aoneban)
___

##### A little bit about me
> I am an innovative, creative developer who is adept at coming up with real solutions that work for clients. As a person, I am pro-active, responsible and quality oriented. I have strong analytical skills and a structured way of working and the courage to try new things. 

used to increase the level of self-education:
- intensive Online Udemi courses, including assignments for practical work, as well as studied online courses on YouTube video hosting;
- solving practical tasks (https://www.codewars.com/, https://leetcode.com/);
- use of official documentation (developer.mozilla.org);
- additional specialized literature;
___

##### Skills
| Hardskills | Softskills|
| ------ | ------ |
| HTML | quick learner |
| CSS | analytical skills |
| JavaScript | detail-oriented|
| React | communication skills |
| Node.js | teamwork|
| TypeScript | problem-solving |

___
##### Code example
```
Given an array of integers, find the one that appears an odd number of times.
There will always be only one integer that appears an odd number of times.

function findOdd(A) {
  const newArr = [];
  const arr = A.reduce((acc, item) => {
    acc[item] = (acc[item] || 0) + 1;
    return acc;
  }, {});
  for (const key in arr) {
    if (arr[key] % 2 !== 0) {
      newArr.push(key);
    }
  }
  return +newArr;
}

[1,2,2,3,3,3,4,3,3,3,2,2,1] should return 4, because it appears 1 time (which is odd).
```




