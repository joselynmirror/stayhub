## Proyecto: Platzi-host

Una aplicación web con:

- Header principal
- Sección hero
- Barra de búsqueda
- Listado de propiedades con cards reutilizables
- Filtros simples por ciudad, tipo o texto
- Estados de carga, error y resultados vacíos

## Tecnologias

- React 19
- Vite
- TypeScript (clases 16–18)

## Datos Mock

El proyecto no tiene backend. Se usaron datos mock para simular las propiedades, ejemplo:

const properties = [
{
id: 1,
title: "Apartamento moderno en Santiago",
location: "Santiago, Chile",
price: 75,
image: "/images/apartment.jpg",
type: "Apartamento"
}
];

## Cómo usar este repositorio

1. Clona el repositorio:

git clone https://github.com/joselynmirror/stayhub.git

2. Instala dependencias:

npm install

3. Levanta el servidor de desarrollo:

npm run dev
