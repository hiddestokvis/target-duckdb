0.8.1 (2025-02-06)
------------------
- Pins DuckDB version to 1.1.3 to ensure capatability with MotherDuck

0.3.0 (2022-04-11)
------------------

- Targets DuckDB 0.3.3
- Supports JSON types for arrays/objects
- Simplifies the project's dependencies

0.2.0 (2022-04-08)
------------------

- Switches to INSERT based loading instead of using COPY CSV operations

0.1.0 (2022-04-07)
------------------

- First basically working version
- Targets DuckDB 0.3.2
- Known limitations:
    - object/array types are treated as varchars
    - primary keys on target tables are disabled
