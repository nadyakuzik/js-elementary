# Javascript Basic Knowledge

- [x] Variables, functions, data types (integer, string, array, object)

```js
/*
  This is comment
*/


// this is comment too

const Nadya888 = {
  name: 'Nadya',
  gender: 'female',
  age: 32,
  car: {
      vin: '02132132132131',
      km: 2123213213
  },
  positive: ['empathy', 'kindness', 'humor'],
  values: [
      { name: 'Квартира', cad: '21321321321' }
  ]
}

function describeNadya (guy) {
  const about = `
    Story about ${guy.name}, ${guy.gender === 'female' ? 'she' : 'he'}  ${guy.age} years old.,
    Car VIN: ${guy.car.vin}
    Values: ${guy.positive.join(', ')}
  `
  return about
}

const aboutNadya = describeNadya(Nadya888)

console.log(aboutNadya)
```

- [ ] Logic: if / else, or, and
- [ ] Iterators: for, while
- [ ] Object / Array methods: forEach, map, filter, reduce

