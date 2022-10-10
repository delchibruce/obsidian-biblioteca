```dataview
TABLE WITHOUT ID  
("![coverimg|100](" + capa +")") AS Capa,  
file.link AS "Título"  
FROM "Biblioteca/Livros"  
WHERE Autor = this.file.link
```
