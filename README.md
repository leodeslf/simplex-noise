# Simplex Noise

```txt
       ______________
      /\            /\
     /\/\  ________/\/\
    /\/\/\/        \/\/    
    \/\/\/\_________\/
     \/\/           /\
      \/_________  /\/\
      /\         \/\/\/\
     /\/\________/\/\/\/
     \/\/          \/\/
      \/____________\/

```

## About

A Simplex Noise library for JavaScript.

## Functions

- `simplex2D`
- `simplex3D`
- `simplex4D`

## Install

```bash
npm i @leodeslf/simplex-noise
```

## Example

```javascript
import { simplex4D } from '@leodeslf/simplex-noise';

console.debug(simplex4D(0, 3, 6, 9.125)); // 0.15430952439664875
console.debug(simplex4D(0, 3, 6, 9.120)); // 0.16308260031261898
console.debug(simplex4D(0, 3, 6, 9.115)); // 0.17172544402554224
```

## Author

[Leonardo de S.L.F](https://github.com/leodeslf "GitHub profile"), original implementation by Stefan Gustavson (Java).

## License

MIT License.
