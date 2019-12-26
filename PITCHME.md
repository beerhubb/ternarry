# ternary 

---

## Agenda

@ol
* Basic `ternary` statement syntaxs
@olend

---

## Basic `ternary` statement syntaxs

```csharp
result = condition ? valueIfTrue: valueIfFalse;
```

+++

## demo 1

```csharp
var vat = 7.0;
var price = 1000;

var amount = vat > 0.0 ? price * (100 + vat) / 100 : price;
```

#### result

```csharp
1070
```
