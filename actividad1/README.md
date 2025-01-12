# README - Botiga Online XML

## Descripció
Aquest document XML conté informació sobre els productes d'una botiga online. Cada producte inclou detalls com el nom, descripció, preu, categoria, disponibilitat i una URL de la imatge.

## Estructura del Document XML

El document XML està organitzat de la següent manera:

- **botiga**: Element arrel que conté tots els productes.
  - **producte**: Cada producte té un atribut `id` per identificació.
    - **nom**: Nom del producte.
    - **descripcio**: Descripció detallada del producte.
    - **preu**: Preu del producte amb un atribut `moneda` per indicar la moneda (en aquest cas, EUR).
    - **categoria**: Categoria a la qual pertany el producte.
    - **disponibilitat**: Indica si el producte està en estoc o esgotat.
    - **imatge**: URL de la imatge del producte.

## Exemple de Producte

A continuació es mostra un exemple de com he defineix un producte en aquest XML:

```xml
<producte id="P001">
    <nom>Portàtil ASUS ROG</nom>
    <descripcio>Portàtil gaming amb processador Intel Core i7, 16GB de RAM i GPU NVIDIA GTX 1660.</descripcio>
    <preu moneda="EUR">1200.00</preu>
    <categoria>Informàtica</categoria>
    <disponibilitat>En estoc</disponibilitat>
    <imatge>https://m.media-amazon.com/images/I/71bxI3BsdaL._AC_SL1500_.jpg</imatge>
</producte>