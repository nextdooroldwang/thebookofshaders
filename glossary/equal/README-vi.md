## Equal
Thực hiện phép so sánh bằng giữa các cặp giá trị của 2 vector.

### Các phiên bản
```glsl
bvec2 equal(vec2 x, vec2 y)  
bvec3 equal(vec3 x, vec3 y)  
bvec4 equal(vec4 x, vec4 y)  

bvec2 equal(ivec2 x, ivec2 y)  
bvec3 equal(ivec3 x, ivec3 y)  
bvec4 equal(ivec4 x, ivec4 y)
```

### Các tham số
```x``` Vector thứ nhất.

```y``` Vector thứ hai.

### Mô tả
```equal()``` trả về một vector boolean mà thành phần thứ ```i``` là kết quả của phép so sánh ```x[i] == y[i]```.

### Tham khảo thêm
[lessThanEqual()](/glossary/?lan=vi&search=lessThanEqual), [lessThan()](/glossary/?lan=vi&search=lessThan), [greaterThanEqual()](/glossary/?lan=vi&search=greaterThanEqual), [greaterThan()](/glossary/?lan=vi&search=greaterThan), [notEqual()](/glossary/?lan=vi&search=notEqual), [any()](/glossary/?lan=vi&search=any), [all()](/glossary/?lan=vi&search=all), [not()](/glossary/?lan=vi&search=not)
