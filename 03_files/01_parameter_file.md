## Parameter File
### Type
1. init file: init{oracle_sid}.ora
  - plan text
2. server parameter file: spfile{oracle_sid}.ora

check value
```sql
select value from v$parameter where name = 'db_block_size'
/
show parameter db_block_s
```




