select (name || '(' || SUBSTR(occupation, 1,1) || ')') from OCCUPATIONS order by name;

select ('There are a total of ' || count(occupation) ||' '|| lower (occupation) || 's.') from OCCUPATIONS GROUP BY occupation ORDER BY COUNT(occupation), occupation ASC;
