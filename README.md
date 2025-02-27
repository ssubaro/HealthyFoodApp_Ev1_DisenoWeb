# 🌟 Proyecto: Nutrition App

## 📋 Descripción
Este proyecto tiene como objetivo desarrollar una aplicación para la gestión de la nutrición, que permita a los usuarios realizar un seguimiento de sus preferencias dietéticas, alergias y metas de salud, recomendando recetas y restaurantes que se ajusten a sus necesidades. La aplicación también estará integrada con datos de actividad física para proporcionar recomendaciones personalizadas, apoyando un enfoque de salud holístico.

---

## 🛠️ Metodología de Trabajo: Agile Scrum
Elegimos la metodología Agile Scrum debido a su capacidad para entregar valor rápidamente y de forma continua. Algunas razones para elegir esta metodología incluyen:

- **Desarrollo Centrado en el Usuario**: A medida que la aplicación maneja preferencias dietéticas y recomienda metas de salud, es crucial obtener retroalimentación continua del usuario para asegurar que el software satisface sus necesidades. Las revisiones de los sprints permiten la participación frecuente de los interesados.
  
- **Requisitos de Integración Complejos**: Funcionalidades como algoritmos de recomendación personalizados, APIs de restaurantes y la integración de aplicaciones de fitness son tecnológicamente complejas. Scrum permite desarrollar primero las funcionalidades básicas e integrar gradualmente las complejidades.
  
- **Cambio en la Ciencia Nutricional**: La flexibilidad de Scrum permite ajustar rápidamente cuando se descubre nueva investigación o cuando los usuarios indican patrones dietéticos nuevos. Las directrices nutricionales son cambiantes, y Scrum se adapta fácilmente a esos cambios.
  
- **Preocupaciones sobre el Tiempo de Mercado**: Es crucial lanzar un producto mínimo viable (MVP) lo antes posible en el competitivo mercado de aplicaciones de salud. Esto es posible gracias al enfoque de Scrum de entregar software funcional en ciclos breves.

---

## 🖼️ Diagramas

### BPMN Diagram

![BPMN Diagram](<BPMN diagram.png>)

### Diagrama de Clases

![Diagrama de Clases](<Class diagrams.png>)

### Diagrama de Actividad

![Diagrama de Actividad](<Activity diagrams.png>)

### Diagrama de Casos de Uso

![Casos de Uso](<Use case diagrams.png>)

---

## 📊 Diagrama ER y Relaciones

### Tablas:

#### Users

![Users](<Table Users.png>)

#### DietaryPreferences

![DietaryPreferences](<Table DietaryPreferences.png>)

#### Allergies

![Allergies](<Table Allergies.png>)

#### Recipes

![Recipes](<Table Recipes.png>)

#### RecipePreferences

![RecipePreferences](<Table RecipePreferences.png>)

#### Restaurants

![Restaurants](<Table Restaurants.png>)

#### RestaurantsMenu

![RestaurantsMenu](<Table RestaurantsMenu.png>)

#### FitnessData

![FitnessData](<Table FitnessData.png>)

#### Recommendations

![Recommendations](<Table Recommendations.png>)

#### Diagrama ER

![DiagramaER](<Diagrama ER.png>)

### Relaciones:
- Un usuario puede tener múltiples preferencias dietéticas y una alergia puede estar asociada con un solo usuario.
- Un usuario puede tener múltiples alergias, pero cada alergia está asociada con un solo usuario.
- Una receta puede tener múltiples preferencias dietéticas, pero cada preferencia dietética pertenece a una única receta.
- Un usuario puede tener múltiples registros de datos de actividad física, pero cada registro pertenece a un solo usuario.
- Un usuario puede tener múltiples recomendaciones, y una recomendación pertenece a un solo usuario.
- Un restaurante puede tener múltiples elementos en su menú, y cada elemento del menú pertenece a un único restaurante.
- Un restaurante puede tener múltiples preferencias dietéticas, pero cada preferencia dietética pertenece a un único restaurante.
- Una recomendación puede estar asociada con una receta y un restaurante.

---

## 💭 Reflexión Personal

### Roberto:
Durante estos primeros meses, aprendí mucho sobre sitios web y bases de datos. Aprendí cómo normalizarlas para que sean más estructuradas y eficientes. Además, revisamos varios diagramas que nos ayudan a construir un sitio web de manera completa. En esta primera evidencia, integré todo lo que aprendí hasta ahora, y ha sido un proceso enriquecedor.

### Pablo:
Hemos aprendido mucho en este primer módulo. En esta evidencia combinamos todo lo aprendido: los tipos de diagramas, cómo adaptar la aplicación y cómo resolver problemas con MySQL. Esta evidencia es la culminación de todo lo que hemos aprendido hasta ahora para nuestra aplicación de nutrición.

### Marlon:
En este módulo, realmente disfruté todos los temas, especialmente los relacionados con bases de datos, diagramas, normalización y SQL. Estos temas son esenciales, ya que nos permiten tener orden en nuestra base de datos y toda la información de la empresa. Estoy emocionado de aprender más en los próximos módulos.

### Patricio:
Lo que vimos en este módulo reforzó mis conocimientos sobre diagramas, frameworks y tecnologías como Git. Aunque el examen no me fue tan bien, me ayudó a entender mejor los conceptos. Esta actividad fue divertida, especialmente el trabajo con bases de datos, y espero ver más sobre esto en los próximos módulos.

