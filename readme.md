# Finder <img src="/img/untitled-1.png" alt="Finder" width="30px">
Bienvenido a **Finder**, la aplicación que te ayuda a encontrar información relevante para ti basada en tu año de nacimiento. Con Finder, podrás descubrir datos interesantes sobre eventos importantes, hitos históricos y culturalmente significativos de la época en la que naciste.

Para comenzar, simplemente ingresa tu año de nacimiento en la pantalla principal y haz clic en "Buscar". En segundos, Finder recopilará datos relevantes de una variedad de fuentes confiables y te presentará una lista de resultados personalizados.

Por ejemplo, si naciste en 1990, Finder te proporcionará información sobre algunos de los eventos más importantes de ese año, como la liberación de Nelson Mandela, la caída del Muro de Berlín y el inicio de la Guerra del Golfo.

Finder es una aplicación increíblemente útil para aquellos que desean descubrir información relevante sobre su año de nacimiento. No importa en qué año naciste, Finder tiene algo para todos. <a href="/index.html">¡Comienza a explorar!</a>

## Caso de Uso
![Caso de uso](/img/caso-de-uso.png)
El código Javascript presentado permite a los usuarios buscar información en la API pública de Wikipedia y obtener resultados en una página web. Por lo tanto, el caso de uso principal sería el de "Buscar información en la API de Wikipedia", que se descompone en los siguientes subcasos de uso:
- Escribir término de búsqueda
- Realizar búsqueda
- Mostrar resultados
- Seleccionar resultado para visualización detallada.

## Diagrama Logico
![Diagrama Fisico](/img/logico.png)
Presenta en el código Javascript consta de dos componentes principales: la interfaz de usuario y la lógica de búsqueda. La interfaz de usuario es responsiva y permite al usuario escribir un término de búsqueda y realizar la búsqueda. La lógica de búsqueda se encarga de conectarse a la API pública de Wikipedia, enviar la consulta de búsqueda y procesar los resultados para mostrarlos en la interfaz de usuario.

## Diagrama Fisico
![Diagrama Logico](/img/fisico.png)
Se observa que la interfaz de usuario se ejecuta en el navegador web del usuario, mientras que la lógica de búsqueda se ejecuta en el servidor de Wikipedia a través de una conexión a Internet. El servidor de Wikipedia se encarga de recibir la solicitud de búsqueda, procesarla y enviar los resultados de vuelta al navegador web del usuario.
