> # String Functions in MySql

> 1. CONCAT
```
SELECT CONCAT("Hi!!", "this", "is", "Harsha.")  # Hii!! this is Harsha.
```

> 2. CONCAT_WS
```
SELECT CONCAT_WS("-", "Hi!!", "this", "is", "Harsha.")  # Hii!!-this-is-Harsha.
```

> 3. GROUP_CONCAT()
```
SELECT col1, col2,...,colN
GROUP_CONCAT( [DISTINCT] col_name1
[ORDER BY clause] [SEPERATOR str_val])
FROM table_name GROUP BY col_name2;
```

> 4. LENGTH
```
SELECT LENGTH("Abc Def")  # 7
```

> 5. SUBSTRING
```
SELECT SUBSTRING("Abc Def", 3, 2)  # c [The length is optional]
```

> 6. SUBSTRING_INDEX
```
SELECT SUBSTRING_INDEX("Abc.Def.Ghi", ".", 2)  # Abc.Def
```

> ## Other: REVERSE(), REPLACE(str, ols, new), UPPER(), LOWER(), REPEAT(str, n) 