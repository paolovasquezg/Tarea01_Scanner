# Tarea01_Scanner

## Autores:
* Paolo Vásquez (202110379)
* Marcelo Zuloeta (202110397)

## Especificaciones

Se tiene el archivo **ejemplo1.sm** con algunas modificaciones:

```
push 3


L1: jmpgt
mul
add
goto L2

```

Para compilar el scanner:

```cpp
g++ -std=c++17 vasquez_zuloeta_scanner_sm.cpp
```

Para ejecutarlo con el archivo **ejemplo1.sm**:

```cpp
./a.out ejemplo1.sm 
```

Con ello obtendra lo siguiente:

```
PUSH
NUM(3)
EOL
LABEL(L1)
JMPGT
EOL
MUL
EOL
ADD
EOL
GOTO
ID(L2)
EOL
END
```
