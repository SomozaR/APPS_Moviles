# verificacion_entorno

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

##########BITACORA 1:

Error 1:
Síntoma:lib/main.dart:77:15: Error: Expected ';' after this.
      _counter+= 2:
              ^^
Causa identificada: Un error de gramatica en el que se ponia doble punto e lugar de punto y coma 
Solución aplicada:Usar el punto y coma en vez de doble punto
Verificación:Aplicar R mayuscula en terminal y esperar que la app corra correctamente despues del hot Reset.

Error 2:
Síntoma:lib/main.dart:129:19: Error: Can't find ']' to match '['.
        children: [
                  ^
lib/main.dart:127:32: Error: Can't find ')' to match '('.
      floatingActionButton: Row(
                               ^
lib/main.dart:89:20: Error: Can't find ')' to match '('.
    return Scaffold(
                   ^
Causa identificada: Un error de estructura en el que no habia cerrado correctamente los las llaves 
Solución aplicada: Buscar las llaves y parentesis abiertas y cerrarlas adecuadamente
Verificación:Aplicar R mayuscula en terminal y esperar que la app corra correctamente despues del hot Reset.