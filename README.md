# 🖩StringCalculatorKata
Kata en Femtech2021🥋

1. Crea una "StringCalculator" que tenga un método `int add(String numbers)`
    - El método puede aceptar 0, 1 o 2 números y devuelve la suma (Si la entrada es un String vacío, la suma es 0), por ejemplo `""`, `"1"` o `"1,2"`
    - Comienza con el caso más simple (String vacío) y continúa con los casos de un número y dos números
    - Recuerda buscar siempre la solución más sencilla
    - Recuerda refactorizar el código cada vez que el test esté pasando

2. Permite que el método `add` reciba cualquier cantidad (desconocida) de números
3. Permite que el método `add` acepte saltos de línea (`\n`) entre números en lugar de comas
    - La siguiente entrada sería válida: `"1\n2,3"` (devuelve 6)
