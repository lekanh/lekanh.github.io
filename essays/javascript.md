---
layout: essay
type: essay
title: Javascript
# All dates must be YYYY-MM-DD format!
date: 2020-01-22
labels:
  - Software Engineering
  - Learning
  - Javascript
---

<img class="ui medium right floated rounded image" src="../images/javascript.png">

I am unfamiliar with Javascript so I was anxious going in. Since I do not know all the advantages and disadvantages, features and bugs of Javascript yet, I cannot really compare it with other programming languages, and determine whether it is a good or bad programming language. However, I had a hard time comprehending certain concepts in regards to ES6, for example:

using arrows functions:
``` javascript
const divide = (dividend, divisor) => dividend * divisor;
```

a variable can be function:

``` javascript
const num = function() {
  const numV = "value";
  return numV;
}
```
which can then can be rewritten as
```
const num = () => "value";
```

or passing an object as a function's parameters by destructuring assignments. That took me off guard as it was very different from C and Java. 
``` javascript
const shape = (shapeData) => {
  const { name, sides, length, width } = shapeData;
```

``` javascript
const shapeUpdate = ({ name, sides, length, width }) => { }
```
## Practice WODs
Practice WODs are very useful, it not only provides exercises which allows more Javascript experiences, we are also told what is wrong with our program in real time and this enables us to learn from our mistakes right away, know why is it wrong, and how it can be fixed. The fact that the practice WODs are not graded allows an easier time for us students, being able to take our time and are not rushed to finish but still know we should utilize our time as much as possible. However, I feel that as the course progresses the WODs difficulity will also progress. The advantage of practice WODs is that it will allow students to have a gauge on difficulties of application of certain concepts better. But it would not be as effective as not all students are able to think on the spot and without any preparations to immediately tackle a difficult program.


## Flipped Classroom
<img class="ui image" src="{{ site.baseurl }}/images/flipped.jpg">

The idea of a flipped classroom seems effective at first glance. I do not find it very enjoyable and I know it does not work for me. Since the materials are all online, there is no way for me to know if the notes I am taking and studying will be of importance, which part I must focus on. Although I do see the appeal of allowing less time on concept explanation and more time for the Professor to apply the concepts to problems to solve during classtime. However, if the student is unable to conceptualize the material, they would end up being confused majority of classtime, trying to both understand the concept and be able to keep up with the application of the concept.
