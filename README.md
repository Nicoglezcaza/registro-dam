# 📋 Registro de Alumno DAM

Aplicación web desarrollada con React y Vite que permite registrar alumnos del ciclo formativo DAM (Desarrollo de Aplicaciones Multiplataforma). El formulario recoge el nombre, email y curso del alumno, genera un objeto JSON con esos datos y los valida en tiempo real aplicando reglas de negocio estrictas definidas con la librería Zod. Si los datos son correctos, se muestra el JSON resultante; si no lo son, se informa al usuario del error concreto detectado.

## 🛠️ Tecnologías utilizadas

- React
- Vite
- Zod

## 🚀 Despliegue en local

​```bash
# 1. Clona el repositorio
git clone https://github.com/Nicoglezcaza/registro-dam.git

# 2. Entra en la carpeta del proyecto
cd registro-dam

# 3. Instala las dependencias
npm install

# 4. Arranca el servidor de desarrollo
npm run dev
​```

## 📦 Diccionario de datos

| Nombre del Campo | Tipo de Dato | Reglas de Validación |
|-----------------|--------------|----------------------|
| `nombre` | `string` | Obligatorio. Mínimo 3 caracteres. |
| `email` | `string` | Obligatorio. Formato de correo electrónico válido. |
| `curso` | `string` | Obligatorio. Solo acepta los valores `"1 DAM"` o `"2 DAM"`. |

---

Desarrollado por **[Nicolás Javier González Cazalla](https://github.com/Nicoglezcaza)**