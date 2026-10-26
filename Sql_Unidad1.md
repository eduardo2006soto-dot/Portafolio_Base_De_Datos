
## 📌 Ejercicios Demostrativos

---

### 🧩 Ejemplo 1 — Sistema de Biblioteca

> Una biblioteca registra libros y autores. Un libro puede tener varios autores y un autor varios libros. Los socios toman libros prestados; de cada préstamo interesan la fecha de retiro y la de devolución.
<img width="1007" height="856" alt="image" src="https://github.com/user-attachments/assets/ac3ea19d-6359-4c27-8f9f-faff6e037ac0" />

---

### 🧩 Ejemplo 2 — Pedidos de Restaurante

> Los clientes realizan pedidos que contienen varios platos con distinta cantidad. Los platos se agrupan en categorías. Cada pedido lo atiende un único mesero. El precio del plato debe registrarse tal como estaba al momento del pedido, aunque luego cambie.
<img width="1401" height="982" alt="image" src="https://github.com/user-attachments/assets/dc5e5524-a89a-46ae-9e71-d7464763d0a0" />

---

### 🧩 Ejemplo 3 — Clínica Médica

> Los pacientes solicitan citas; cada cita la atiende un médico a un paciente en fecha, hora y consultorio. De algunas citas se genera una receta que incluye medicamentos con dosis y duración. Cada médico pertenece a una especialidad.
<img width="1333" height="1050" alt="image" src="https://github.com/user-attachments/assets/da258fc3-c63c-4f76-8f87-81b4876dd7bb" />

---

### 🧩 Ejemplo 4 — Sistema de Aerolínea

> Una aerolínea opera vuelos (cada uno con número, fecha, origen y destino), cada vuelo lo realiza un avión. Los pasajeros realizan reservas para un vuelo específico, indicando asiento y tarifa pagada en el momento de la reserva.
<img width="1027" height="737" alt="image" src="https://github.com/user-attachments/assets/682d3e90-2aa4-4444-9ae3-6a588044f734" />


---

## 📌 Ejercicios Propuestos

---

### 🧩 Ejercicio 5 — Empresa Discográfica

Una empresa discográfica necesita modelar los datos sobre sus diferentes recursos según las siguientes características:

* **Manager:** De cada mánager se almacena un identificador de manager y su nombre. Un manager representa a una serie de artistas.
* **Artista:** Un artista es representado por un manager. De los artistas se almacena su nombre completo (usando un único atributo) y su NIF.
* **Evento de promoción:** Los artistas participan en eventos de promoción para dar a conocer sus trabajos. En un evento de promoción pueden participar varios artistas. De un evento se almacena un identificador único, la fecha de celebración y el número de asistentes.
<img width="972" height="617" alt="image" src="https://github.com/user-attachments/assets/5b409d00-473e-457a-90a9-ef138fec3be4" />


---

### 🧩 Ejercicio 6 — Tienda Informática

Se desea crear una aplicación para la gestión de una tienda informática. 

* La tienda dispone de una serie de productos que se venden a los clientes. De cada producto informático se desea guardar el código, descripción, precio y número de existencias. 
* De cada cliente se desea guardar el código, nombre, apellidos, dirección y número telefónico. Un cliente puede comprar varios productos en la tienda y un mismo producto puede ser comprado por varios clientes. 
* Cada vez que se compre un artículo quedará registrada la compra en la base de datos junto con la fecha en la que se compró el artículo. 
* La tienda tiene contactos con varios proveedores que son los que suministran los productos. Un mismo producto puede ser suministrado por varios proveedores. De cada proveedor se desea guardar el código, nombres, apellidos, dirección, provincia y número de teléfono.
<img width="711" height="952" alt="image" src="https://github.com/user-attachments/assets/67dc1cdb-2181-4046-ba56-8c6aed8c1973" />

---

### 🧩 Ejercicio 7 — Discos Musicales

* La tienda vende discos de diferentes géneros musicales y cantantes.
* Cada género musical tiene un identificador.
* Cada disco tiene título, género musical, precio y cantante.
* De un cantante se registra el nombre y su país. Todo disco pertenece a un cantante y un cantante puede tener muchos discos. Además, un disco tiene un conjunto de canciones (identificador y título).
* Un disco tiene muchas canciones y una canción puede estar en varios discos. Interesa conocer la posición de una canción en un determinado disco.
<img width="948" height="865" alt="image" src="https://github.com/user-attachments/assets/f0bde4b3-f106-40f0-9265-dfffdc9f623e" />

---

### 🧩 Ejercicio 8 — Camiones

Se desea informatizar la gestión de una empresa de transporte que reparte paquetes por toda España. 

* Los encargados de llevar los paquetes son los camioneros, de los que se quiere guardar la cédula, nombre, teléfono, dirección, salario y población en que vive. 
* De los paquetes transportados interesa conocer el código del paquete, descripción, destinatario y dirección del destinatario.
* Un camionero distribuye muchos paquetes, y un paquete sólo puede ser distribuido por un camionero. 
* De las provincias a las que llegan los paquetes interesa guardar el código de provincia y el nombre. Un paquete sólo puede llegar a una provincia. Sin embargo, a una provincia pueden llegar varios paquetes.
* De los camiones que llevan los camioneros, interesa conocer la matrícula, modelo, tipo y potencia. Un camionero puede conducir diferentes camiones en fechas diferentes, y un camión puede ser conducido por varios camioneros.
<img width="1265" height="967" alt="image" src="https://github.com/user-attachments/assets/aac65a00-efa8-4007-98a8-8469f3ec8478" />

---

### 🧩 Ejercicio 9 — Veterinaria

* Del **propietario** interesa: cédula, apellidos, nombres, dirección y teléfonos.
* De la **mascota** interesa: identificador, nombre, fecha de nacimiento y tipo. Un propietario puede llevar una o varias mascotas; una mascota la lleva uno y solo un propietario.
* Del **personal** de la clínica veterinaria interesa un código, la cédula y nombre. Entre el personal de la clínica se distingue a los **veterinarios** y los **auxiliares**, pudiendo haber otros tipos:
  * Del **veterinario** se guarda además su fecha de alta y especialidad.
  * De los **auxiliares** interesa su base de cotización.
* Las mascotas pasan consulta con los veterinarios. De manera que:
  * Un veterinario puede pasar consulta a ninguna o a varias mascotas.
  * Una misma mascota de la clínica ha pasado consulta una o más veces en fechas diferentes con varios veterinarios.
  * Al pasar consulta se realiza un diagnóstico.
* Cada propietario tiene un **familiar de contacto** para casos de emergencia. De este familiar interesa la cédula, nombre y teléfono. Si el propietario se da de alta en la clínica veterinaria, el familiar ya no interesa. El familiar es contacto de un solo propietario.
<img width="1352" height="1048" alt="image" src="https://github.com/user-attachments/assets/0f9d70ba-b7b3-4bb8-b1fe-cdcdfbfe0e2d" />

---

<p align="center">
  <a href="https://github.com/eduardo2006soto-dot/Portafolio_Base_De_Datos/blob/main/README.md">
    <img src="https://img.shields.io/badge/⬅️_VOLVER_AL_PORTAFOLIO-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Volver al portafolio">
  </a>
</p>

<p align="center">
  <sub>💻 Universidad Nacional de Loja · Carrera de Computación · Base de Datos · 2026</sub>
</p>

---
