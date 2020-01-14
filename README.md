# oracle-listener-support-no-service
oracle-listener-support-no-service

```
sqlplus /nolog
conn /as sysdba
alter system set local_listener='(DESCRIPTION=(ADDRESS=(PROTOCOL=tcp)(HOST=localhost)(PORT=1521)))' sid='ORCL' scope=spfile;
```
