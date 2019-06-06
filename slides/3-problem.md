# What's wrong with JavaScript?

---

## JavaScript is a silent killer

<img src="killer.gif" width="25%" />

---

## [The "Wat" talk by Gary Bernhardt](https://www.destroyallsoftware.com/talks/wat)

---

```javascript
> [] + []
```

---

```javascript
> [] + []
''
```

---

```javascript
> [] + {}
```

---

```javascript
> [] + {}
'[object Object]'
```

---

```javascript
> {} + []
```

---

```javascript
> {} + []
0
```

---

```javascript
> {} + {}
```

---

```javascript
> {} + {}
NaN
```

---

- JavaScript fails silently when faced with obvious type errors.


- This is much worse than most other duck-typed languages.

