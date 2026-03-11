# Seminario de Actualización 2 - Actividades Web

**Autor:** Colman Máximo  
**Fecha:** Marzo 2026

---

## Descripción General

Este repositorio contiene tres actividades prácticas desarrolladas como parte del Seminario de Actualización 2. Cada actividad demuestra diferentes conceptos de desarrollo web, desde aplicaciones frontend puras hasta servidores con Node.js y Python.

### Actividades Incluidas:

1. **Actividad-1**: Aplicación web interactiva (HTML, CSS, JavaScript vanilla)
2. **Actividad-2**: Servidor backend con Express.js (Node.js)
3. **Actividad-3**: Servidor backend con Python HTTP

---

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener instalados:

- **Node.js** (versión 14 o superior) - [Descargar aquí](https://nodejs.org/)
- **Python** (versión 3.8 o superior) - [Descargar aquí](https://www.python.org/)
- **Git** - [Descargar aquí](https://git-scm.com/)

Para verificar las instalaciones, ejecuta en tu terminal:

```bash
node --version
npm --version
python --version
```

---

## 🚀 Clonación del Repositorio

Clona el repositorio en tu máquina local usando el siguiente comando:

```bash
git clone <URL_DEL_REPOSITORIO>
cd seminario-de-actualizaci-n-2-colman-maximo
```

Después de clonar, verás la siguiente estructura:

```
.
├── Actividad-1/
├── Actividad-2/
├── Actividad-3/
└── README.md
```

---

## 📁 Estructura de Carpetas

### Actividad-1
```
Actividad-1/
├── index.html      # Estructura HTML de la aplicación
├── index.js        # Lógica JavaScript del cliente
└── style.css       # Estilos CSS
```

### Actividad-2
```
Actividad-2/
├── package.json    # Dependencias del proyecto Node.js
├── servidor.js     # Servidor Express
└── public/
    ├── index.html
    ├── index.js
    └── style.css
```

### Actividad-3
```
Actividad-3/
├── index.html      # Estructura HTML
├── index.js        # Lógica JavaScript del cliente
├── servidor.py     # Servidor Python HTTP
└── style.css       # Estilos CSS
```

---

## 💻 Instrucciones de Uso

### **Actividad-1: Aplicación Web Interactiva**

Esta actividad es una aplicación frontend que no requiere servidor. Simplemente abre el archivo HTML en tu navegador.

**Pasos:**

1. Navega a la carpeta:
   ```bash
   cd Actividad-1
   ```

2. Abre el archivo `index.html` con tu navegador preferido (puedes hacer doble clic en el archivo o arrastrar de allí al navegador).

3. ¡La aplicación estará lista para usar! Ingresa texto en el campo de entrada y presiona Enter o haz clic en el botón "Transformación".

---

### **Actividad-2: Servidor Node.js con Express**

Esta actividad utiliza Express.js para servir una aplicación web.

**Pasos:**

1. Navega a la carpeta:
   ```bash
   cd Actividad-2
   ```

2. Instala las dependencias del proyecto:
   ```bash
   npm install
   ```

3. Inicia el servidor en modo de desarrollo:
   ```bash
   npm run dev
   ```

   O si prefieres ejecución sin recargar automáticamente:
   ```bash
   node servidor.js
   ```

4. Abre tu navegador y ve a:
   ```
   http://localhost:3000
   ```

5. Para detener el servidor, presiona `Ctrl + C` en la terminal.

**Nota:** El servidor utiliza el puerto 3000 y sirve los archivos desde la carpeta `public/`.

---

### **Actividad-3: Servidor Python HTTP**

Esta actividad utiliza un servidor HTTP nativo de Python para servir archivos estáticos.

**Pasos:**

1. Navega a la carpeta:
   ```bash
   cd Actividad-3
   ```

2. Asegúrate de tener Python instalado:
   ```bash
   python --version
   ```

3. Inicia el servidor:
   ```bash
   python servidor.py
   ```

   Deberías ver un mensaje similar a:
   ```
   Servidor funcionando en http://localhost:5000
   ```

4. Abre tu navegador y ve a:
   ```
   http://localhost:5000
   ```

5. Para detener el servidor, presiona `Ctrl + C` en la terminal.

**Nota:** El servidor utiliza el puerto 5000 y sirve los archivos desde la carpeta `public/`.

---

## 🔧 Diferencias Entre Actividades

| Aspecto | Actividad-1 | Actividad-2 | Actividad-3 |
|---------|-------------|-------------|------------|
| **Tipo** | Frontend puro | Backend (Node.js) | Backend (Python) |
| **Servidor requerido** | No | Sí (Express) | Sí (HTTP nativo) |
| **Puerto** | N/A | 3000 | 5000 |
| **Dependencias** | Ninguna | npm (Express) | Python nativa |
| **Comando ejecución** | Abrir HTML | `npm run dev` | `python servidor.py` |

---

## 🐛 Solución de Problemas

### El servidor no inicia en Actividad-2
- Verifica que el puerto 3000 esté disponible
- Si ya hay algo usando el puerto, puedes cambiar el `PORT` en `servidor.js`

### El servidor Python no inicia en Actividad-3
- Asegúrate de estar en la carpeta correcta
- Verifica que la carpeta `public/` exista
- Si el puerto 5000 está en uso, modifica el `PORT` en `servidor.py`

### Los estilos no se cargan correctamente
- Verifica que los archivos `style.css` estén en el mismo directorio que `index.html`
- Revisa la consola del navegador (F12) para mensajes de error

---

## 📝 Notas Importantes

- **Actividad-1** es funcional sin servidor web
- **Actividad-2** y **Actividad-3** necesitan ejecutarse desde terminal/consola
- Todos los servidores pueden ejecutarse simultáneamente en diferentes puertos
- En caso de cambiar puertos, actualiza también la URL en el navegador

---

## 📚 Referencias

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Express.js Guide](https://expressjs.com/)
- [Python HTTP Server](https://docs.python.org/3/library/http.server.html)
- [MDN Web Docs](https://developer.mozilla.org/)

---

**Desarrollado por:** Colman Máximo  
**Última actualización:** Marzo 2026
