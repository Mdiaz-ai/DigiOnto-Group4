# Justificación de Campos Descartados

Durante el análisis de las fuentes de datos originales, hemos decidido no modelar ni incluir los siguientes campos en los requisitos funcionales de nuestra ontología, por las razones de diseño que se exponen a continuación:

* **`Number` (Dataset DigiDB)**: Se descarta este campo porque es puramente un identificador numérico interno (índice) de la base de datos relacional original. En nuestra ontología, utilizaremos el propio nombre de la criatura (campo `Digimon`) como identificador único con valor semántico.
* **`Equip Slots` (Dataset DigiDB)**: Este campo indica cuántos objetos puede equiparse un Digimon dentro de las mecánicas concretas de un videojuego específico (ej. *Cyber Sleuth*). Se ha descartado porque nuestra ontología se centra en las características biológicas, evolutivas y de combate intrínsecas del ecosistema Digimon, dejando fuera mecánicas de inventario de software de terceros.
