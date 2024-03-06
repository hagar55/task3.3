select sum(CITY.population) from CITY , COUNTRY
where CITY.CountryCode =  COUNTRY.Code and CONTINENT='Asia';
