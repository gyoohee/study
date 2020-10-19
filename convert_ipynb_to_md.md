## PostgreSQL Summary

1. 테이블명 변경


```python
ALTER TABLE table_name RENAME TO new_name;
```

2. 컬럼명 변경


```python
ALTER TABLE table_name RENAME COLUMN a_name TO b_name;
```

3. 컬럼 타입 변경


```python
ALTER TABLE table_name ALTER COLUMN column_name TYPE NUMERIC(2,0);
```

4. 컬럼 삭제


```python
ALTER TABLE table_name DROP column_name;
```

## Pandas DataFrame


```python
import pandas as pd
temp_df = pd.DataFrame({'name':['Alice', 'Bob', 'Chris'], 'Age':[20, 50, 15]})
temp_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>20</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>50</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Chris</td>
      <td>15</td>
    </tr>
  </tbody>
</table>
</div>


