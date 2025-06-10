# Exercicis

## Exercicis - Nivell bàsic

### Exercici 1

**a)** Escriu un programa que imprimisca l'area d'un quadrat de costat 5.  
**b)** Modifica'l perquè el costat del quadrat s’introduïsca per teclat i es mostre l'area corresponent.  
**c)** Afig-hi el càlcul i la mostra del perímetre del mateix quadrat.  

### Exercici 2

**a)** Escriu un programa que llig dos nombres i només mostre la seua suma.  
**b)** Ampli­a'l perquè també mostre la resta dels dos nombres.  
**c)** Afig-hi el producte i la divisió, mostrant cada resultat amb un missatge clar.  
**d)** Afig que, en cas de dividir per zero, no farà l'operació i mostrarà un missatge indicant de l'error.  

### Exercici 3

**a)** Escriu un programa que demane l’edat per teclat i, si l’usuari és major d’edat (≥18), mostre "Ets major d’edat".  
**b)** Modifica’l perquè, en cas contrari, mostre "Ets menor d’edat".  
**c)** Afig-hi una comprovació addicional: si l’edat introduïda és negativa, que mostre "Error: edat invàlida".  

## Exercicis - Nivell mitjà

### Exercici 4

**a)** Crea un programa que, donat un número introduït per teclat, imprimirà tots els números entre 0 i aquest.  
**b)** Afig una comprovació prèvia que ens assegure que el número introduït és positiu.  
**c)** Modifica el programa de forma que només imprimirà els números parells i no siguen ni 16 ni múltiples de 3.  

### Exercici 5

En el departament de secretaria t’han demanat un programa per convertir notes numèriques en valoracions alfabètiques.

**a)** El programa llig una nota (0–10) i escriu la corresponent valoració:

- 0–2: Molt deficient
- 3–4: Insuficient
- 5–6: Bé
- 7–8: Notable
- 9–10: Excel·lent

**b)** Si la nota està fora de l’interval 0–10, ha de mostrar “Error: nota invàlida”.  
**c)** Afig una felicitació addicional: si la qualificació és exactament 10, també mostrarà “Felicitats! Tens matrícula d'honor!”.  

## Exercicis - Nivell alt

### Exercici 6

Una botiga ven banderes personalitzades de la màxima qualitat i ens ha demanat fer un configurador que calcule el preu segons alt i ample. El preu base d'una bandera és d’un cèntim d’euro el centímetre quadrat. Si la volem amb un escut brodat, el preu s'incrementa en 2,50 € independentment de l'escut. Les despeses d'enviament són 3,25€. L'IVA ja està inclòs a totes les tarifes.

*Exemple*:

```plaintext
Introduïu l'alçada de la bandera en cm: 20
Ara introduïu l'amplada: 35  
Vol escut brodat? (s/n): n  
Gràcies. Aquí teniu el desglossament de la vostra compra.  
Bandera de 700 cm2: 7,00 €  
Sense escut: 0,00 €  
Despeses d'enviament: 3,25 €  
Total: 10,25 €  
```

### Exercici 7

Una pastisseria ens ha demanat fer un programa que faça pressupostos de pastissos. El programa preguntarà primer de quin sabor vol l'usuari el pastís: poma, maduixa o xocolata. El pastís de poma val 18 euros i el de maduixa 16. En cas de seleccionar el pastís de xocolata, el programa ha de preguntar a més si la xocolata és negra o blanca; la primera opció val 14 euros i la segona 15. Finalment, es pregunta si s'hi afegeix nata i si es personalitza amb un nom; la nata suma 2,50 i l'escriptura del nom 2,75.

*Exemple*:

```plaintext
Trieu un sabor (poma, maduixa o xocolata): xocolata
Quin tipus de xocolata voleu? (negre o blanc): negre
Vol nata? (si o no): si
Voleu posar-hi un nom? (si o no): no
Pastís de xocolata negra: 14,00 €
Amb nata: 2,50 €
Total: 16,50 €
```

### Exercici 8

Implementa el joc pedra, paper y tisora. Primer, l’usuari 1 introdueix la seua jugada y després l’usuari 2.

*Exemple 1*:

```plaintext
Torn del jugador 1 (introdueix pedra, paper o tisora): paper
Torn del jugador 2 (introdueix pedra, paper o tisora): paper
Empat
```

*Exemple 2*:

```plaintext
Torn del jugador 1 (introdueix pedra, paper o tisora): paper
Torn del jugador 2 (introdueix pedra, paper o tisora): tisora
Guanya el jugador 2
```

*Exemple 3*:

```plaintext
Torn del jugador 1 (introdueix pedra, paper o tisora): pedra
Torn del jugador 2 (introdueix pedra, paper o tisora): tisora
Guanya el jugador 1
```
