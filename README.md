# 🥗 Contador de Calorías

Aplicación desarrollada por **Jeziel Leyton** que permite llevar un control de calorías consumidas y quemadas. Diseñada para ser parte de mi portafolio como desarrollador frontend. Esta herramienta permite registrar actividades con sus respectivas calorías y categorizarlas según si son alimentos o ejercicios.

## ✨ Características

- Registro de actividades (consumo o quema de calorías)
- Cálculo automático de calorías consumidas y quemadas
- Visualización de resumen
- Interfaz responsive y estilizada con Tailwind CSS
- Arquitectura con `useReducer` para manejo eficiente del estado
- Tipado estricto con TypeScript

## 🚀 Tecnologías utilizadas

- ⚛️ [React](https://reactjs.org/)
- ⛑️ [TypeScript](https://www.typescriptlang.org/)
- 💨 [Tailwind CSS](https://tailwindcss.com/)
- ⚙️ [Vite](https://vitejs.dev/) como entorno de desarrollo
- 📦 Reducers personalizados para manejo de estado

## 📂 Estructura del proyecto

```
contadorcalorias/
├── src/
│   ├── components/       # Componentes reutilizables
│   ├── data/             # Datos simulados o estáticos
│   ├── reducers/         # Reducers para el manejo de estado
│   ├── types/            # Definiciones de tipos TypeScript
│   ├── App.tsx           # Componente raíz
│   └── main.tsx          # Punto de entrada principal
├── index.html
├── tailwind.config.js
├── vite.config.ts
└── README.md
```

## 🧠 Lógica del proyecto

La aplicación gestiona las actividades mediante `useReducer`, lo que permite:

- Agregar nuevas actividades
- Filtrar por categoría (alimentación o ejercicio)
- Calcular automáticamente las calorías totales usando `useMemo`



Este proyecto está disponible bajo la licencia [MIT](LICENSE).

---

Creado  por **Jeziel Leyton**
