---
id: 587d824c367417b2b2512c4f
title: Test if a Value Falls within a Specific Range
challengeType: 2
videoUrl: ''
localeTitle: ''
---

## Description
undefined

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=9").then(data => {assert.equal(data.state,"passed"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=9").then(data => {  assert.equal(data.assertions[0].method, "approximately");  assert.equal(data.assertions[0].args[2], 0.5, "weirdNumbers(0.5) is in the range (0.5, 1.5]. It\"s within 1 +/- 0.5"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=9").then(data => {  assert.equal(data.assertions[1].method, "approximately");  assert.equal(data.assertions[1].args[2], 0.8, "weirdNumbers(0.2) is in the range (0.2, 1.2]. It\"s within 1 +/- 0.8"); }, xhr => { throw new Error(xhr.responseText); })'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
