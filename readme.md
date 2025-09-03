# oefeningen deel 2

## exceptions

Onderstaande stukken code geven een foutmelding, vang deze op gepaste wijze op.
In commentaar staat voor de eerste 3 oefeningen het type foutmelding, voor de laatste 2 moet je het bekijken in de terminal van vscode.

Maak per oefening een nieuw bestand aan

```python
# ZeroDivisionError
def deel(a, b):
    resultaat = a / b
    print(f"Resultaat: {resultaat}")

deel(10, 0)
```

```python
#TypeError
def tel_op(a, b):
    return a + b

tel_op(5, "drie")
```

```python
#IndexError
lijst = [10, 20, 30]

print(lijst[5])

```

```python
persoon = {"naam": "Ali", "leeftijd": 30}

print(persoon["adres"])

```

```python
invoer = "abc"
    getal = int(invoer)

```

## gebruik maken van matplotlib

Voor deze opgaves moet je de matplotlib geïnstalleerd hebben. Dit doe je met onderstaand commando in de terminal van VScode

```cmd
pip install matplotlib
```

De eerste regels code krijg je telkens.

1. Plot een eenvoudige lijn van y = 2x

```python
x = list(range(0, 11))
y = [2 * i for i in x]
```

2. Vergelijk y = x, y = x^2 en y = x^3

```python
x = list(range(0, 11))
y1 = x
y2 = [i**2 for i in x]
y3 = [i**3 for i in x]
```

3. Visualiseer de frequentie van letters in een woord

```python
from collections import Counter

woord = "matplotlib"
frequentie = Counter(woord)
```

4. Visualiseer verdeling van tijd per activiteit

```python
activiteiten = ["Studeren", "Sport", "Slapen", "Vrije tijd"]
uren = [5, 2, 8, 9]
```

5. Toon spreiding van 2 variabelen

```python
x = [random.randint(1, 100) for _ in range(50)]
y = [i + random.randint(-10, 10) for i in x]
```
