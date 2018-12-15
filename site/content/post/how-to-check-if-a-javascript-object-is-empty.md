---
title: How To Check If A Javascript Object Is Empty
date: 2018-12-15T14:10:30.643Z
description: >-
  Javascript is the most unpredictable language, they say !!! I say, so are we.
  The Human Beings !!
---
The safest/easiest way to check empty object is here 

```
isEmptyObject(obj) {    
        return JSON.stringify(obj) === JSON.stringify({});
}

```
