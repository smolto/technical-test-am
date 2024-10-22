# Prueba Técnica de React

---

**Objetivo:** Construir una aplicación simple de React para evaluar tus habilidades en la creación y gestión de componentes, uso de hooks, manejo de eventos y lógica de negocio.

---

### Contexto:

Imagina que estás desarrollando un e-commerce de camisetas deportivas (Futbol Factory, Futbol Emotion). Los usuarios pueden agregar una camiseta a la lista de favoritos, añadirla al carrito y eliminarla tanto de la lista como del carrito. Además, pueden filtrar por texto.

---

### Requisitos:

1. **Componentes:**
    - Crea un componente  que será el contenedor principal de la aplicación.
    - Crea un componente que permita a los usuarios ver la lista de camisetas.
    - Crea un componente de paginación
    - Crea un componente que permita agregar las camisetas a la lista de favoritos.
    - Crea un componente que permita filtrar entre las camisetas.
    - Crea un componente de carrito con un formulario para “registrar” una solicitud por esa camiseta.
    - Crea un selector de talla de tipo radio button
2. **Filtros:**
    - Search Bar que puedes buscar por el nombre de la camiseta.
3. **Estilos:**
    - Aplica algunos estilos básicos a la aplicación para que sea visualmente atractiva.

---

### Información adicional:

1. **Camisetas:** La base de datos debe ser un JSON en el propio proyecto. La información que se debe guardarse es:
    - Nombre
    - Marca
    - Precio
    - Talla
    - Imagen

```json
{
	"name": "Camiseta 1ª Levante UD 2024/2025",
	"brand": "Macron"
	"price": 74.95,
	"sizes": ["S", "M", "L", "XL"],
	"img": "https://static.futbolfactory.es/products/249024_1.webp"
}
```

1. **Formulario:** Solicitar los siguientes datos al usuario con sus validaciones
    - Nombre y apellidos.
    - Email.
    - Teléfono
    - Ciudad
    - Código Postal

---

### Criterios de Evaluación:

- **Estructura del código**: Separación adecuada de componentes, organización de carpetas y claridad del código.
- **Uso correcto de hooks**: Implementación de `useState` y otros hooks relevantes.
- **Funcionalidad**: Que la aplicación cumpla con los requisitos y que las funcionalidades principales funcionen correctamente.
- **Calidad del código**: Buenas prácticas en cuanto a la legibilidad y comentarios del código.
- **Estilos**: Que la aplicación tenga un diseño limpio y funcional, aunque no es necesario que sea un diseño complejo.

---

### Entrega:

Sube tu proyecto a un repositorio público de GitHub y comparte el enlace. Asegúrate de incluir instrucciones claras en el `README.md` para instalar las dependencias y ejecutar la aplicación.
