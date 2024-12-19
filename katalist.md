**Friend of foe**

```TypeScript
export function friend(friends: string[]): string[] { 
  const output: string[] = [];
  for (let i = 0; i < friends.length; i++) {
    if (friends[i].length === 4) {
      output.push(friends[i]);
    }
  }
  return output;
}
```

**Beginner Series #3 Sum of Numbers**

```TypeScript
export function getSum(a: number, b: number): number {
  if (a == b) {
    return a;
  }
  if (b > a) {
    let c: number = a;
    a = b;
    b = c;
  }
  let output: number = b;
  for (let i = b + 1; i <= a; i++) {
    output += i;
  }
  return output;
}
```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```

**T**

```TypeScript

```