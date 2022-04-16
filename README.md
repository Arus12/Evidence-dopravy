# Evidence autobusů
- Práce na PHP a JavaScript – Černý
- Práce na HTML, SCSS a MySql – Rutte
- Zařízení hostingu – Černý a Rutte

Tento program má za úkol uložit do databáze obdržená data odpovídající zadaným pravidlům a následně je zobrazit chronologicky pod sebe na hlavní stránku. Při tvorbě byli použity technologie HTML, SCSS, CSS, MySql, PHP a JavaScript. Webová stránka běží na URL adrese: ## http://evidencedopravy.xf.cz/
![image](https://user-images.githubusercontent.com/74651859/163685290-51364d81-439d-4631-9078-c89209d1a3a1.png)



## HTML a CSS

Pomocí HTML byl vytvořen základní Layout stránek a tomu byl dán vzhled za použití technologie SCSS, která po potvrzení vytvořila soubor CSS. Ten už přímo dává vzhled HTML. Mezi vzhledy patří barvy, hlavička, hodiny, vzhled tlačítek, dotazníku a vzhled tabulky.
![image](https://user-images.githubusercontent.com/74651859/163685291-62b4ebb4-b4d8-4e49-a814-b0eb1fdf5326.png)
![image](https://user-images.githubusercontent.com/74651859/163685315-1301b7d1-3900-4deb-8244-0747449b79e8.png)
![HTML screen](https://user-images.githubusercontent.com/74651859/163685318-30886eb3-2be4-4db2-ac1e-75486588b344.png)
![SCSS](https://user-images.githubusercontent.com/74651859/163685322-6d02c4c1-eef6-48e8-9f47-e3447bd2d275.png)

## MYSql

Databáze, která slouží jako prostor pro ukládání a k pozdějšímu volání dat na hlavní stránku byla vytvořena za použití MySql. Databáze komunikuje s HTML stránkou za pomocí PHP kódu.
![image](https://user-images.githubusercontent.com/74651859/163685380-93b1e02c-bb2c-42ee-b856-cc3e68525a55.png)
![image](https://user-images.githubusercontent.com/74651859/163685400-7a1ee1b7-fca8-4bfe-a9aa-c7c340e0079e.png)

## PHP
PHP má za úkol obstarat samotnou komunikaci databáze se stránkou. Mezi hlavní funkce patří připojování do databáze, přidávání spojů a času do již zmíněné databáze, a reset celého systému. Jeho dalším úkolem je updatovat data do CSV souboru které pak míří do databáze.
![PHP](https://user-images.githubusercontent.com/74651859/163685431-8ac31d8c-15b4-40a3-8952-25ccfd20e7a6.png)
![Loader](https://user-images.githubusercontent.com/74651859/163685432-5a430b70-5892-4d56-a97d-4c081f862d76.png)

## JavaScript
JavaScript má za úkol zobrazit všechny spoje a srovnat je pro uživatele podle časové osy. Zobrazuje celkový obsah stránky.
![JavaScript](https://user-images.githubusercontent.com/74651859/163685449-e4b5d808-2754-4371-854d-a14270b0afcc.png)

