# Battery

```bash
weexpack plugin add nat-device-battery
```

### status(callback)

#### Arguments
1. [`callback`] (Function)

#### Returns
1. `result` (Object)
    - `level` (Int) (0~100)
    - `isPlugged` (Boolean)

#### Example
```js
Nat.battery.status((err, ret) => {
    console.log(ret)
})
```
