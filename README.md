# reto_tecnico_banco_pichincha

Reto Técnico: App de Recetario

Crear una aplicación de Android que permita al usuario explorar un recetario de
cocina, ver detalles recetas y marcarlas como favoritas.

1. Splash Screen
        ◦ Aparece al abrir la aplicación.
        ◦ Debe desaparecer automáticamente después de 2 segundos.
   
2. Onboarding
    ◦ Consta de 3 pantallas consecutivas para presentar información ficticia sobre la app (por ejemplo, cómo buscar recetas, marcar favoritas, etc.).
    ◦ Este onboarding solo debe mostrarse la primera vez que se abre la aplicación.
   
3. Pantalla Principal
    ◦ Presenta un listado de recetas obtenidas desde una API por el desarrollador.
    ◦ Cada receta debe incluir al menos:
        ▪ Nombre.
        ▪ Una imagen.
        ▪ Descripción breve.
    ◦ Permitir al usuario seleccionar recetas como favoritas y mostrar una sección separada para estas.
    ◦ La lista debe actualizarse dinámicamente cuando se marquen o desmarquen recetas como favoritas.
   
4. Pantalla de Detalle de Receta
    ◦ Muestra información detallada de una receta seleccionada:
        ▪ Nombre.
        ▪ Imagen.
        ▪ Ingredientes.
        ▪ Pasos para preparar la receta.
   
5. Modo Oscuro (Dark Mode)
    ◦ La aplicación debe adaptarse automáticamente al modo oscuro configurado en el sistema.

Requisitos Técnicos
    • La API puede ser creada con cualquier herramienta (e.g., Postman, Mockoon, o un servidor temporal).
    • Usar MVVM (o una arquitectura propuesta por el candidato).
    • Manejo de dependencias con Dagger Hilt.
    • Implementar persistencia local para las recetas marcadas como favoritas.


Pruebas
    • Incluir pruebas unitarias para al menos un caso de uso.


Evaluación
    1. Calidad del código: Limpieza, modularidad y legibilidad.
    2. Buenas prácticas: Uso de patrones y librerías modernas.
    3. Pruebas: Cobertura adecuada de lógica principal y flujos clave.
    4. Experiencia de usuario (UX): No se evalúa un diseño perfecto, pero la aplicación debe ser intuitiva y entendible para el usuario.
