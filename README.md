# Predictor de Ruleta Argentina

![Demo](screenshot.png)

Sistema de aprendizaje automático que predice números en la ruleta argentina basado en patrones históricos.

## Características principales
- Sistema de aprendizaje continuo
- Almacenamiento local de datos
- Análisis estadístico en tiempo real
- Interfaz responsive
- Historial de predicciones

## Cómo usar
1. Ingresa números históricos (0-36) en el campo de entrada
2. Haz clic en "Predecir próximo" para obtener una estimación
3. Cuando se revele el número real, ingrésalo en el campo de feedback
4. El sistema aprenderá automáticamente de los resultados

## Requisitos técnicos
- Navegador moderno (Chrome, Firefox, Edge)
- Conexión a internet (para cargar librerías)

## Instalación
No requiere instalación. Solo abre el archivo `index.html` en tu navegador.

## Configuración
Los datos se guardan automáticamente en el almacenamiento local del navegador.

## Limitaciones
- Requiere mínimo 5 números para hacer predicciones
- Mejora su precisión con más datos (óptimo >30 números)
- La ruleta es un juego de azar, las predicciones son probabilísticas

## Cómo contribuir
1. Haz fork del proyecto
2. Crea una rama con tus cambios (`git checkout -b feature/mejora`)
3. Haz commit de tus cambios (`git commit -am 'Agregar mejora'`)
4. Haz push a la rama (`git push origin feature/mejora`)
5. Abre un Pull Request