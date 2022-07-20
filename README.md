# sqlodev3
Patika Sql Ödev-3

Cevap-1:
select * from country where country like 'A%a';

Cevap-2:
select * from country where length(country)>6 and country like '%n';

Cevap-3:
select title from film where length(title)>4 or title ilike '%T%';

Cevap-4:
select * from film where length(title)>90 or title like 'C%' and rental_rate=2.99;
