# Estudos SQL

## Filtro
> `WHERE nome LIKE 'j%'`
- filtra campos que **começam** com J
> `WHERE nome LIKE '%j%'`
- filtra campos que **tenham** J

**para filtrar texto, precisa ser LIKE**

## Operadores
```jsx
<> não igual a 
!= diferente de
(A diferença entre eles é apenas aonde são usados, mas cumprem a mesma função)
> maior que 
< menor que
>= maior ou igual
<= menor ou igual
```

## Operadores Lógicos
```jsx
AND
OR
BETWEEN (4 and 7) ou NOT BETWEEN (4 and 7)
    IN e NOT IN {
  SELECT * FROM table WHERE column_name IN (1,3,5)
}
IS NULL e IS NOT NULL
```


INSERT INTO aluno (nome, cpf, responsavel) VALUES ("Jose Vitor", 06512390020, "Maria")

UPDATE aluno SET nome='Vitor M', responsavel='Jose R' WHERE matricula = 2

DELETE FROM aluno WHERE matricula = 3
