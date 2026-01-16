## Bronze layer
- Tranforms data from `source database` to `default database` in the same catalog
- There are 3 methids to config model
-> 1. Write in `dbt_project.yml`
-> 2. Create `properties.yml` in the folder that `.sql file`. And config it inside.
-> 3. config by the top of the `.sql file` by following this pattern `{{config(materialized='view')}}`by `view` can change to `table. This method calls 'blocks'
