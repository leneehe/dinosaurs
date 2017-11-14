1. SELECT COUNT(*) FROM dinos;
2. SELECT * FROM dinos WHERE period = 'Jurassic';
3. SELECT SUM(length) FROM dinos WHERE period = 'Cretaceous';
4. SELECT * FROM dinos WHERE period = 'Jurassic' OR period = 'Cretaceous' ORDER BY species;
5. SELECT * FROM dinos WHERE t_order='Saurischia' AND diet='Herbivorous';
6. SELECT name FROM dinos WHERE length = (SELECT MIN(length) FROM dinos);
UPDATE dinos SET name = 'Shortie' WHERE name = 'Liaoxiornis';
7. SELECT * FROM dinos ORDER BY name LIMIT 1;}
