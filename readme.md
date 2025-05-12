Juego Educativo: Prevención del Desgaste Profesional
Este proyecto es un juego educativo interactivo diseñado para enseñar a los trabajadores sobre las causas del síndrome de desgaste profesional (burnout) y los factores de riesgo psicosocial en el entorno laboral. A través de escenarios realistas, los usuarios pueden aprender a identificar y manejar situaciones relacionadas con las demandas de trabajo excesivas, falta de control, problemas de liderazgo y desequilibrio esfuerzo-recompensa.
Mostrar imagen
📋 Contenido

Acerca del proyecto
Objetivos educativos
Implementación
Estructura del proyecto
Personalización
Uso con GitHub Pages
Licencia

🔍 Acerca del proyecto
El síndrome de desgaste profesional (burnout) es un problema de salud laboral cada vez más frecuente que afecta la productividad, el bienestar y la salud de los trabajadores. Este juego educativo proporciona una forma interactiva y participativa para que los empleados aprendan sobre los factores de riesgo psicosocial que pueden conducir al burnout y desarrollen estrategias para prevenirlo.
El juego "Equilibrio Laboral" permite a los usuarios enfrentarse a diferentes situaciones laborales donde deben tomar decisiones para mantener un entorno laboral saludable. Las elecciones del usuario afectarán cuatro áreas clave relacionadas con los factores de riesgo psicosocial:

Gestión de demandas laborales
Control sobre el trabajo
Calidad del liderazgo y relaciones sociales
Satisfacción con las recompensas

🎯 Objetivos educativos

Concienciar sobre el síndrome de desgaste profesional y sus causas
Identificar los factores de riesgo psicosocial en el entorno laboral
Desarrollar estrategias efectivas para prevenir el burnout
Fomentar una cultura organizacional saludable
Promover el bienestar psicológico en el trabajo

💻 Implementación
El juego está desarrollado como una aplicación web utilizando HTML, CSS y JavaScript. Todo el contenido se encuentra en un solo archivo HTML, lo que facilita su implementación en cualquier servidor web o plataforma de alojamiento.
Requisitos técnicos

Navegador web moderno (Chrome, Firefox, Safari, Edge)
Conexión a internet (solo para la carga inicial)

No se requieren instalaciones adicionales ni dependencias externas.
🏗️ Estructura del proyecto
El proyecto consta de un único archivo HTML que integra:
index.html
├── Información educativa sobre el burnout
├── Juego interactivo "Equilibrio Laboral"
│   ├── Sistema de puntuación
│   ├── Escenarios laborales
│   └── Retroalimentación educativa
└── Recursos adicionales
Componentes principales

Sección informativa: Proporciona datos educativos sobre el síndrome de desgaste profesional, sus síntomas y factores de riesgo.
Juego interactivo: Presenta escenarios laborales con múltiples opciones de respuesta, cada una con diferentes impactos en las áreas de riesgo psicosocial.
Sistema de puntuación: Realiza un seguimiento de cómo las decisiones del usuario afectan a las cuatro áreas clave de riesgo psicosocial.
Análisis de resultados: Al finalizar el juego, proporciona un análisis personalizado basado en las decisiones tomadas y ofrece recomendaciones para mejorar.

✏️ Personalización
El juego puede personalizarse fácilmente para adaptarse a diferentes sectores laborales o necesidades específicas:
Modificar escenarios
Los escenarios se definen en el arreglo scenarios dentro del script JavaScript. Cada escenario tiene:
javascript{
    id: 1,
    title: "Título del escenario",
    description: "Descripción de la situación",
    options: [
        {
            text: "Opción 1",
            impact: { demands: +10, control: -5, leadership: 0, reward: +5 },
            feedback: {
                type: "positive", // o "negative"
                message: "Mensaje de retroalimentación"
            }
        },
        // Más opciones...
    ]
}
Para añadir nuevos escenarios, simplemente añada objetos adicionales al arreglo, siguiendo la misma estructura.
Modificar estilos
Los estilos visuales se definen en la sección <style> del documento HTML. Se utiliza CSS puro, por lo que es fácil modificar colores, fuentes y diseño:
css:root {
    --primary: #3498db;    /* Color principal */
    --secondary: #2ecc71;  /* Color secundario */
    --warning: #e74c3c;    /* Color de advertencia */
    --dark: #34495e;       /* Color oscuro */
    --light: #ecf0f1;      /* Color claro */
}
🚀 Uso con GitHub Pages
Para implementar este juego en GitHub Pages:

Crear un repositorio en GitHub
Subir el archivo index.html al repositorio
Activar GitHub Pages en la configuración del repositorio:

Ir a "Settings" > "Pages"
En "Source", seleccionar "main" y guardar


Acceder a la URL proporcionada por GitHub Pages (generalmente https://[username].github.io/[repository-name])

📄 Licencia
Este proyecto está disponible bajo la licencia MIT, lo que permite su uso, modificación y distribución libremente, siempre que se mantenga el aviso de copyright y de licencia.
👥 Contribuciones
Las contribuciones son bienvenidas. Si desea mejorar este juego educativo, puede:

Fork el repositorio
Crear una rama para su funcionalidad (git checkout -b feature/nueva-funcionalidad)
Hacer commit de sus cambios (git commit -m 'Añadir nueva funcionalidad')
Push a la rama (git push origin feature/nueva-funcionalidad)
Abrir un Pull Request

📞 Contacto
Para preguntas, sugerencias o soporte, por favor abra un issue en el repositorio o contacte al administrador.

Este juego educativo no sustituye la formación profesional sobre salud laboral ni el asesoramiento de profesionales de la salud ocupacional. Es una herramienta complementaria diseñada con fines educativos.
