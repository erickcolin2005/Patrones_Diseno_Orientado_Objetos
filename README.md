# Patrones de Diseño Orientado a Objetos (UCC-PDOO)

Repositorio de la materia **Patrones de Diseño Orientado a Objetos** (Universidad Cooperativa de Colombia). Reúne ejemplos de patrones de diseño, ejercicios de las sesiones de clase, talleres, examen y el proyecto final, implementados en **Java** (proyectos NetBeans / Ant).

Autor: **Erick Collin Albornoz** ([@erickcolin2005](https://github.com/erickcolin2005))

---

## 📁 Estructura del repositorio

| Carpeta | Contenido |
|---|---|
| [`ejemplos-patrones/`](ejemplos-patrones) | Ejemplos sueltos de patrones (un solo archivo fuente cada uno) |
| [`sesiones/`](sesiones) | Ejercicios de las sesiones de clase (proyectos NetBeans) |
| [`proyectos-netbeans/`](proyectos-netbeans) | Proyectos NetBeans temáticos completos |
| [`talleres/`](talleres) | Talleres de la sección 3 |
| [`examen/`](examen) | Examen — Momento 2 |
| [`proyecto-final/`](proyecto-final) | Proyecto final (historias de usuario + simulación) |

---

## 🧩 Ejemplos de patrones

Ejemplos didácticos donde cada `Main.java` define todas las clases del patrón.

| Ejemplo | Patrón / Tema |
|---|---|
| [abstract-factory](ejemplos-patrones/abstract-factory) | Abstract Factory (cuentas y tarjetas de banco) |
| [factory-method](ejemplos-patrones/factory-method) | Factory Method (farmacia / medicamentos) |
| [builder](ejemplos-patrones/builder) | Builder (paciente) |
| [prototype](ejemplos-patrones/prototype) | Prototype |
| [singleton](ejemplos-patrones/singleton) | Singleton (banco) |
| [bancos](ejemplos-patrones/bancos) | Cuenta bancaria |
| [manufactura-acero](ejemplos-patrones/manufactura-acero) | Manufactura de acero (máquinas / turnos) |
| [manufactura-costos](ejemplos-patrones/manufactura-costos) | Manufactura de costos |
| [recreacion](ejemplos-patrones/recreacion) | Recreación |
| [transporte](ejemplos-patrones/transporte) | Transporte |

## 🗓️ Sesiones de clase

Proyectos NetBeans desarrollados en cada sesión.

| Sesión | Patrón / Tema |
|---|---|
| [seccion-03](sesiones/seccion-03) | Logger |
| [seccion-07-objectpool](sesiones/seccion-07-objectpool) | Object Pool |
| [sesion-08](sesiones/sesion-08) | Adapter y Bridge (facturación, GPS, reporte vehículo) |
| [sesion-09](sesiones/sesion-09) | Rastreo |
| [sesion-10](sesiones/sesion-10) | Composite y Decorator (archivos, menú web, notificaciones, café) |
| [sesion-11](sesiones/sesion-11) | Facade (hotel) |

## 💼 Proyectos NetBeans

| Proyecto | Patrón / Tema |
|---|---|
| [builder-boletos](proyectos-netbeans/builder-boletos) | Builder (boletos) |
| [factory-prestamos](proyectos-netbeans/factory-prestamos) | Factory (préstamos: personal, hipotecario, automotriz) |
| [juego-lucha](proyectos-netbeans/juego-lucha) | Juego de lucha (personajes / guerreros) |

## 🧪 Talleres, examen y proyecto final

- [`talleres/`](talleres) — taller-seccion3-ejercicio1, taller-seccion3-ejercicio2
- [`examen/momento-2`](examen/momento-2) — ejercicio5 (Auto), ejercicio7 (MedicalRecord)
- [`proyecto-final/`](proyecto-final) — Historia7, Historia8 y SimulacionTerminal

---

## 🛠️ Cómo ejecutar

Los proyectos son de **NetBeans (Ant)**. Para cada uno:

1. Abrir la carpeta del proyecto en NetBeans (la que contiene `build.xml`).
2. *Clean and Build* y luego *Run*.

Los ejemplos sueltos de [`ejemplos-patrones/`](ejemplos-patrones) se compilan y ejecutan directo:

```bash
javac Main.java && java Main
```

> Los artefactos compilados (`*.class`, `build/`, `dist/`) están excluidos vía `.gitignore`: se regeneran al compilar.

## 📚 Referencias

- [Refactoring.Guru — Patrones de diseño](https://refactoring.guru/es/design-patterns)
- *Sumérgete en los Patrones de Diseño* — Alexander Shvets
