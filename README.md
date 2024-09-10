# Command Pattern

Command es un patrón de diseño de comportamiento que convierte una solicitud en un objeto independiente que contiene toda la información sobre la solicitud. Esta transformación te permite parametrizar los métodos con diferentes solicitudes, retrasar o poner en cola la ejecución de una solicitud y soportar operaciones que no se pueden realizar.

# Analogía en el mundo real

![imagenprueba](https://refactoring.guru/images/patterns/content/command/command-comic-1.png?id=551df832f445080976f3116e0dc120c9)


Tras un largo paseo por la ciudad, entras en un buen restaurante y te sientas a una mesa junto a la ventana. Un amable camarero se acerca y toma tu pedido rápidamente, apuntándolo en un papel. El camarero se va a la cocina y pega el pedido a la pared. Al cabo de un rato, el pedido llega al chef, que lo lee y prepara la comida. El cocinero coloca la comida en una bandeja junto al pedido. El camarero descubre la bandeja, comprueba el pedido para asegurarse de que todo está como lo querías, y lo lleva todo a tu mesa.

El pedido en papel hace la función de un comando. Permanece en una cola hasta que el chef está listo para servirlo. Este pedido contiene toda la información relevante necesaria para preparar la comida. Permite al chef empezar a cocinar de inmediato, en lugar de tener que correr de un lado a otro aclarando los detalles del pedido directamente contigo.

# Pseudocódigo
El patrón Command ayuda a rastrear el historial de operaciones ejecutadas y hace posible revertir una operación si es necesario.
![pseudocodigo](https://refactoring.guru/images/patterns/diagrams/command/example.png?id=1f42c8395fe54d0e409026b91881e2a0)

# Referencias

https://refactoring.guru/es/design-patterns/command
