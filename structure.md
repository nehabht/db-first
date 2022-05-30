# library

## modello car

### table cars


- id: BIGINT, PRIMARYKEY, AI UNIQUE
- model: VARCHAR(10) NOTNULL
- price: DECIMAL(8, 2) 999999,99 NULL
- year: YEAR NOTNULL
- manufacturer: VARCHAR(50) NOTNULL
- model: VARCHAR(50) NOTNULL
- odometer: MEDIUMINT NOTNULL
- type: VARCHAR(20) NOTNULL
- Valves per cylinder: TINYINT NOTNULL
- used: BOOL NOTNULL 
- seats: TINYINT NULL
- fueltype: VARCHAR(20) NOTNULL
- trasmission: VARCHAR(50) NOTNULL
- vehicle weight: MEDIUMINT NULL
- additional features: TEXT NULL