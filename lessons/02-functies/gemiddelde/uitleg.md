Een lijst bewaart meerdere waarden onder één naam. Elke waarde heeft een **index**: haar plaats in de lijst,
geteld vanaf 0.

![De lijst getallen = [7, 3, 9, 4] met de indexen 0 tot 3](media/lijst.png)

```python
getallen = [7, 3, 9, 4]
print(getallen[0])     # 7
print(len(getallen))   # 4
print(sum(getallen))   # 23
```

Het **gemiddelde** van $n$ getallen $x_1, x_2, \ldots, x_n$ is

$$\bar{x} = \frac{x_1 + x_2 + \cdots + x_n}{n}$$

Voor de lijst hierboven is dat $\frac{23}{4} = 5{,}75$.

> [!TIP]
> `sum(lijst)` telt alle getallen op en `len(lijst)` geeft het aantal: meer heb je niet nodig.

> [!WARNING] Een lege lijst
> Een lege lijst heeft lengte 0, en delen door 0 geeft een fout (`ZeroDivisionError`).
