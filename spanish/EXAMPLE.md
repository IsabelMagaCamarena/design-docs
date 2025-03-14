# PetGlam BOT
Link: [https://github.com/IsabelMagaCamarena/design-docs/edit/patch-1/spanish/EXAMPLE.md](#)

Author(s): Isabel Magaña

Status: Primera version

Ultima actualización: 2025-03-08

## Contenido
- Goals
- Non-Goals
- Background
- Overview
- Detailed Design
- Consideraciones
- Métricas

## Objetivo
Un bot que brinde informacion de las caracteristicas de tu mascota y las necesidades sobre el cuidado de su piel y pelaje.

## Goals
- Indentificar los tipos de raza de tu mascota para brindar la informacion adecuada.
  
## Non-Goals
- Brindar informacion erronea acerca de los cuidados del perro.

## Background
Los clientes suelen tener ideas equivocadas de los cuidados necesarios de su mascota, el cual los lleva a realizarle servicios que perjudican la salud y bienestar de los mismos.

## Overview
Necesitamos una API para reconocer la raza del perro en la imagen. Luego, con una base de datos propia o integrada con fuentes confiables, podemos proporcionar información sobre el tipo de piel y pelaje, junto con recomendaciones de cuidado (tipo de shampoo, frecuencia de baño, cepillado, etc.).

## Detailed Design
Implementación Básica
Recibir imágenes de los usuarios.
Enviar la imagen a un modelo de IA para identificar la raza.
Consultar la base de datos y devolver información sobre la raza, tipo de piel y pelaje.
Enviar recomendaciones de cuidados al usuario.

## Consideraciones
- Encontrar un buscador inteligente para la compartiva de las fotos de las mascotas.
