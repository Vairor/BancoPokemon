1)use pokedex

2)desc pokemon

3)select * from pokemon

4)select numero, nome, cor, altura_m e peso_kg from pokemon

5)select numero, nome from pokemon
where geracao = 1

6)select numero, nome from pokemon
where geracao = 1 and cor = "amarelo"

7)select nome from pokemon
order by total desc
limit 1

8)select nome, numero, tipo1 from pokemon
where tipo1 = "fire"

9)select nome, numero, defesa from pokemon order by  defesa desc

10)select nome, total from pokemon
order by taxa_captura desc
limit 1

11)select nome from pokemon
where  tipo2 IS NULL

12)select numero, nome, tipo1, tipo2 from pokemon
where  peso_kg between 100 and 500

13)select numero, nome, velocidade from pokemon
order by velocidade desc limit 10

14)select numero, nome, tipo1, tipo2, taxa_captura from pokemon
where tipo2 IS NOT NULL and taxa_captura >100 order by taxa_captura desc

15)select distinct tipo1 from pokemon

16)select numero, nome, cor from pokemon
where nome like "d%" or "D%"

17)select nome from pokemon
order by total desc
limit 1

18)select numero, nome, defesa from pokemon
where defesa >60 and ataque <=70
order by total desc

19)select nome from pokemon
where tipo1 = "planta"
and tipo2 = "venenoso"
and cor <> "Green"
order by nome asc

20)select nome from pokemon
where nome like "%   Y%" or "%   y%"
order by nome asc


21)select ataque_especial from pokemon
order by ataque_especial desc
limit 1

22)select nome, numero, altura_m from pokemon
where altura_m > 2.10

23)select distinct cor from pokemon
order by cor asc

24)select nome, velocidade from pokemon
where velocidade between 30 and 70
order by nome asc;

select nome, velocidade from pokemon
where velocidade between 30 and 70
order by velocidade desc

25)select nome, total from pokemon
where lendario = true
order by total desc

26)select nome from pokemon
where geracao = 1
and taxa_captura = 255

27)select nome from pokemon
where nome in ("pikachu","bulbasaur","charmander","squirtle")
order by total desc

28)select nome, taxa_captura from pokemon
where geracao = 1
and nome like "d%"
and tipo2 is null
order by nome asc;

select nome, taxa_captura from pokemon
where geracao = 1
and nome like "d%"
and tipo2 is null
order by taxa_captura desc

29)select numero, nome, total, taxa_captura from pokemon
where lendario = true
order by taxa_captura desc
limit 5;
select numero, nome, total, taxa_captura from pokemon
where lendario = true
order by total desc
limit 5

30)select numero, nome, peso_kg from pokemon
where peso_kg between 3 and 4

31)select numero, nome, tipo1, tipo2 from pokemon
where tipo1 = "normal" and tipo2 is null
and lendario = false

32)select numero, nome, tipo1, tipo2, cor from pokemon
where tipo1 = "water"
and cor  <>"blue"
order by nome asc

33)select nome, velocidade from pokemon
order by velocidade asc
limit 10

34)select nome, velocidade from pokemon
where nome like "a%"
and nome like "%a"

35)select numero, nome, tipo1, tipo2, cor from pokemon
where tipo1 = "fire"
and cor  <>"red"
order by nome asc

36)select distinct peso_kg from pokemon
order by peso_kg asc

37)select numero,nome, hp from pokemon
where nome between 0 and 100
and numero between 0 and 100
and hp between 0 and 100
order by nome asc;

select numero,nome, hp from pokemon
where nome between 0 and 100
and numero between 0 and 100
and hp between 0 and 100
order by hp asc

38)select numero, nome, hp, ataque, defesa, total from pokemon
where hp>= 100
and ataque >=100
and defesa >= 100

39)select nome from pokemon
where tipo1 = "water"
and tipo2 = "gelo"
order by total desc
