# KAITA μν¬μ π

μΉ΄μ΄ν μν¬μμμ λ§λ  νλ‘μ νΈ μλλ€ π
 
[κΉνλΈ νλ‘μ νΈ μλλ€](https://github.com/bryantson/kaita-workshop)

![μ΄λ―Έμ§](images/background.jpg)

μ²μ νλ‘μ νΈλ₯Ό λ§λ€κΈ° μν λ μνΌ

- μμ΄ν 1

## μ½λ© λ°λΌ ν΄λ΄μλ€

λ°λΌν΄λ³΄κΈ°

### μ€ν νκΈ° 

#### μ€ν 1

`npm install`

#### μ€ν 2

`npm start`

### μ€ν 3

`docker build -t kaita-app:1.0`

### μ½λ© μ€ν¬λ¦½νΈ

```javascript
// Express λΌμ΄λΈλ¬λ₯Ό μλλ€
const express = require("express")

// express νλ μμν¬λ₯Ό μ¬μ©ν΄μ μ±μ μ μ ν©λλ€:
const app = express()

// Public ν΄λ μμ μ ν¬κ° νμν μΉμ¬μ΄νΈ νμΌμ΄ μλ€κ³  λ§ν©λλ€
app.use(express.static("public"))

```

## Contribution νλ λ°©λ²

μ¬κΈ°λ₯Ό μ°Έκ³ νμΈμ

[Contribution.md](CONTRIBUTION.md)