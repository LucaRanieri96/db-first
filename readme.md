# Database Used Cars

## data types:
- String: [varchar(number), char(number), text, longtext]
- numbers: [tinyint, small/medium int, int, bigint]
- decimals: [float(i,d), double(i,d), decimal(i,d)]
- dates: DATETIME, DATE, TIME, YEAR, TIMESTAMP

## attributes:

- PK(chiave primaria)
- AI(auto increment)
- NN(not null)
- NULL
- UNIQUE(che non si ripete)

## Entity name: Car

## Table name: Cars

## Table columns: 
- id: numero della riga | BIGINT | PK, AI, NN, UNIQUE

- model: VARCHAR(200), NN
- car_brand: VARCHAR(200), NN
- fuel_type: VARCHAR(50), NULLABLE
- engine_size: DECIMAL(4,1), NULLABLE 
- horsepower:  SMALLINT, NULLABLE
- color: VARCHAR(50), NULLABLE
- condition: VARCHAR(50), NULLABLE
- year | YEAR, NULLABLE
- year_of_enrollment | YEAR, NULLABLE
- km | BIGINT, NULLABLE
- note | TEXT, NULLABLE
- photos | VARCHAR(255), NULLABLE