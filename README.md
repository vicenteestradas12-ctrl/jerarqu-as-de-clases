# jerarqu-as-de-clases
<p align="center">
  <img src="image(1).png" width="700">
</p>

# LlanquihueTourApp

## Información General

**Asignatura:** Desarrollo Orientado a Objetos I

**Estudiante:** Vicente Estrada

**Fecha:** 08/06/2026

---

# Objetivo de esta semana

Implementar una jerarquía de clases utilizando herencia dentro del sistema LlanquihueTourApp.

Se desarrolló una estructura orientada a objetos que permite representar distintos servicios turísticos ofrecidos por la agencia mediante una superclase y múltiples subclases, aplicando principios de encapsulamiento, reutilización y organización modular.

---

# Estructura del Proyecto

```text
src
│
├── model
│   ├── ServicioTuristico.java
│   ├── RutaGastronomica.java
│   ├── PaseoLacustre.java
│   └── ExcursionCultural.java
│
├── data
│   └── GestorServicios.java
│
└── ui
    └── Main.java
```

---

# Clases Creadas

## ServicioTuristico

Clase base del sistema.

### Atributos

* nombre
* duracionHoras

---

## RutaGastronomica

Hereda de ServicioTuristico.

### Atributo adicional

* numeroDeParadas

---

## PaseoLacustre

Hereda de ServicioTuristico.

### Atributo adicional

* tipoEmbarcacion

---

## ExcursionCultural

Hereda de ServicioTuristico.

### Atributo adicional

* lugarHistorico

---

## GestorServicios

Clase encargada de crear instancias de prueba para verificar el funcionamiento del sistema.

Funciones:

* Crear dos rutas gastronómicas.
* Crear dos paseos lacustres.
* Crear dos excursiones culturales.
* Mostrar resultados por consola.

---

## Main

Clase principal del programa.

Responsabilidad:

* Ejecutar el sistema.
* Llamar al gestor.
* Mostrar información utilizando `toString()`.

---

# Instrucciones para Ejecutar Main

1. Abrir el proyecto en IntelliJ IDEA.
2. Verificar que la estructura de paquetes esté correcta.
3. Compilar el proyecto.
4. Abrir:

```text
ui/Main.java
```

5. Ejecutar el método `main()`.
6. Revisar la salida en consola.

---

# Resultado Esperado

```text
RUTA GASTRONÓMICA
Nombre: Sabores del Sur
Duración: 4 horas
Número de paradas: 5

PASEO LACUSTRE
Nombre: Lago Llanquihue
Duración: 2 horas
Tipo embarcación: Catamarán

EXCURSIÓN CULTURAL
Nombre: Museo Colonial
Duración: 5 horas
Lugar histórico: Frutillar
```

---

# Tecnologías Utilizadas

* Java
* IntelliJ IDEA
* GitHub
* Programación Orientada a Objetos

---

# Autor

Vicente Estrada

Duoc UC

08/06/2026
