# 🧾 Generador de Reporte de Pago para Programadores

Este programa en Java recopila información de un programador, calcula su tarifa por hora con base en la experiencia, y genera un reporte detallado con pagos por cliente, descuentos e impuestos.

---

## 🛠️ Correcciones realizadas

Este proyecto se inició con varios errores de sintaxis, lógica y uso de librerías. A continuación, se detallan los problemas y las soluciones implementadas:

### ❌ Errores detectados y ✅ soluciones

| Tipo           | Error Original                                                  | Corrección Realizada                                        |
|----------------|-----------------------------------------------------------------|--------------------------------------------------------------|
| Importación    | No se importó `Scanner` ni `LocalDate`                          | Se agregaron `import java.util.Scanner;` y `java.time.LocalDate;` |
| Sintaxis       | `System.out.print"Ingrese...`                                   | Cambiado a `System.out.print("Ingrese...");`                |
| Sintaxis       | `scanner`, `system`, `leer`, `nex`, `nextline()` incorrectos   | Se cambió a `Scanner sc = new Scanner(System.in);` y `sc.nextLine();`, etc. |
| Tipos          | `tarifaBase = 50,0,0;`                                          | Corregido a `tarifaBase = 50.0;`                            |
| Lógica         | Cálculo de pagos usaba variables mal escritas (`Cliene`, `Fnal`) | Nombres corregidos: `bonusCliente1`, `tarifaHoraFinal`, etc. |
| Declaraciones  | Comentarios bloqueaban ejecución de lectura de horas (`sc.nextInt();`) | Se descomentaron y corrigieron                             |
| Sintaxis       | `====` usado en lugar de `=`                                   | Corregido a `subtotal = ...`                                |

---

## 🚀 Cómo ejecutar

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tuusuario/ReportePagoProgramador.git
    cd ReportePagoProgramador
    ```

2. Compila el archivo Java:
    ```bash
    javac src/org/example/Main.java
    ```

3. Ejecuta el programa:
    ```bash
    java org.example.Main
    ```

---

## 💡 Tecnologías usadas

- Java 17+
- IntelliJ IDEA / VS Code (opcional)
- Línea de comandos

---

## 📄 Licencia

Este proyecto es de código abierto bajo la licencia MIT.

