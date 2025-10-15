# 🎮 Sudoku Game

Un juego de Sudoku interactivo y moderno creado con HTML, CSS y JavaScript puro.

## 🌟 Características

- ✨ Interfaz visual moderna y atractiva
- 🎯 Tres niveles de dificultad (Fácil, Medio, Difícil)
- ⏱️ Temporizador integrado
- 🔢 Contador de errores
- 💡 Sistema de pistas
- ✅ Verificación de solución
- 🤖 Resolución automática
- 📱 Diseño responsive (funciona en móviles y tablets)
- ⌨️ Navegación con teclado (flechas)

## 🚀 Demo en Vivo

[Ver Demo](https://tu-usuario.github.io/sudoku) *(Actualizar después de desplegar)*

## 🎮 Cómo Jugar

1. Selecciona un nivel de dificultad
2. Haz clic en "Nuevo Juego"
3. Haz clic en cualquier celda vacía para seleccionarla
4. Ingresa números del 1 al 9
5. Usa las flechas del teclado para moverte entre celdas
6. Las celdas se marcarán en verde si el número es válido, o en rojo si hay conflictos
7. Completa todo el tablero para ganar

### Controles

- **Nuevo Juego**: Genera un nuevo puzzle
- **Verificar**: Comprueba si tu solución actual es correcta
- **Pista**: Revela un número correcto en una celda aleatoria
- **Resolver**: Muestra la solución completa del puzzle

## 📦 Instalación Local

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/sudoku.git
cd sudoku
```

2. Abre `index.html` en tu navegador web favorito

¡No se requieren dependencias ni instalación adicional!

## 🌐 Despliegue en GitHub Pages

### Opción 1: Desde la interfaz web de GitHub

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, haz clic en **Pages**
4. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`
5. Haz clic en **Save**
6. Espera unos minutos y tu sitio estará disponible en `https://tu-usuario.github.io/sudoku`

### Opción 2: Usando Git desde la terminal

```bash
# Inicializar repositorio (si aún no lo has hecho)
git init

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Initial commit: Sudoku game"

# Agregar repositorio remoto
git remote add origin https://github.com/tu-usuario/sudoku.git

# Subir a GitHub
git push -u origin main
```

Luego sigue los pasos de la Opción 1 para activar GitHub Pages.

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura del juego
- **CSS3**: Estilos y animaciones
- **JavaScript (ES6+)**: Lógica del juego
  - Generación de tableros usando backtracking
  - Validación de movimientos
  - Resolución automática de puzzles

## 📁 Estructura del Proyecto

```
sudoku/
│
├── index.html          # Estructura HTML principal
├── styles.css          # Estilos y diseño
├── script.js           # Lógica del juego
└── README.md          # Este archivo
```

## 🎯 Algoritmo

El juego utiliza el algoritmo de **backtracking** para:
- Generar tableros válidos de Sudoku
- Resolver puzzles automáticamente
- Validar movimientos del jugador

## 🔮 Futuras Mejoras (Ideas para nuevas ramas)

- 💾 Guardar progreso en localStorage
- 🏆 Sistema de puntuación y récords
- 🎨 Temas de color personalizables
- 📊 Estadísticas de juego
- 🔊 Efectos de sonido
- 👥 Modo multijugador
- 📝 Notas en celdas (números pequeños)
- ↩️ Deshacer/Rehacer movimientos

## 👨‍💻 Autor

Tu Nombre

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

## 🙏 Agradecimientos

Proyecto creado como parte de una actividad académica.
