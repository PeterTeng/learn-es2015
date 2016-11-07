# Memo

## Class

```javascript
class Hello {
  constructor(name) {
    this.name = name;
  }

  bark() {
    return `Hello, I am ${this.name}`;
  }
}

module.exports = Hello;
```

👇


```javascript
export default class {
  constructor(name) {
    this.name = name;
  }

  bark() {
    return `Hello, I am ${this.name}`;
  }
}
```

## import

```javascript
const gulp = require('gulp');
const exec = require('child_process').exec;
```

👇

```javascript
import gulp from 'gulp';
import { exec } from 'child_process';
```
