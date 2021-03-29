# Use constants inside regex formatter

```
  a = r"^AP-rna-\d+\.csv$"
  b = r"^[a-zA-Z]{2}-[a-zA-Z]{3}-\d+\.csv$"

  f"({a}|{b})"
```



