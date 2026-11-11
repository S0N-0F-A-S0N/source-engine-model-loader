## 2024-03-24 - [Typed Arrays memcopy Optimization]
**Learning:** Typed array `set` with `subarray` is significantly faster (~1000x) than manual element-by-element assignment using a for loop in JavaScript, especially for large buffers.
**Action:** Prefer `TypedArray.prototype.set` instead of `for` loops when copying buffers.
