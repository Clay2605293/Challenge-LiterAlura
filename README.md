# Challenge-LiterAlura
Reto del programa ONE para desarrollar una aplicación backend en JAVA que tome datos de una API pública de libros (Gutendex),
guarda los datos consultados en una BD de PostgreSQL y los muestra.

# Requrimientos
Se requiere Maven JDK 17 y PostgreSQL.

En el archivo application.properties se define:

spring.datasource.url=jdbc:postgresql://localhost:5432/alura
spring.datasource.username=postgres
spring.datasource.password=pass

Esos datos pueden cambiar. Para usar por default se necesita una BD llamada alura, con usuario postgresy password pass.

# Uso
La aplicación funciona como se muestra a continuación:

<img width="447" alt="Screenshot 2024-07-13 at 1 00 46 p m" src="https://github.com/user-attachments/assets/97e6400d-98cb-45a9-88d4-6e9ddab41daa">
<img width="408" alt="Screenshot 2024-07-13 at 9 09 55 p m" src="https://github.com/user-attachments/assets/074f3fa3-43f9-4eed-9e49-0c6c64a841fc">
<img width="370" alt="Screenshot 2024-07-13 at 9 10 10 p m" src="https://github.com/user-attachments/assets/ca307f56-6fa2-4402-b587-8979d7ceac3a">
<img width="475" alt="Screenshot 2024-07-13 at 9 10 23 p m" src="https://github.com/user-attachments/assets/0b9a4787-f165-40de-96e9-028b4b9785c9">
<img width="481" alt="Screenshot 2024-07-13 at 9 10 41 p m" src="https://github.com/user-attachments/assets/2c19f052-1b2b-4aad-a12a-5ae644abd575">
<img width="490" alt="Screenshot 2024-07-13 at 9 10 52 p m" src="https://github.com/user-attachments/assets/c55f5765-b073-4baf-9868-c6bd7a6c0d6d">
<img width="1376" alt="Screenshot 2024-07-13 at 9 11 08 p m" src="https://github.com/user-attachments/assets/9dc4bba5-ca9e-402e-a4b6-dc54276cef82">

Y la base de datos se ve algo como esto:
<img width="562" alt="Screenshot 2024-07-13 at 10 49 54 p m" src="https://github.com/user-attachments/assets/53f113cb-b357-40b0-831b-fc9df6ed76c4">
<img width="779" alt="Screenshot 2024-07-13 at 10 50 04 p m" src="https://github.com/user-attachments/assets/eb287f57-413b-4460-98b8-90ed6b831144">
