# Chuleta de Altair

### Import
```python
import pandas as pd
import altair as alt
```

### Bar Chart
```python
alt.Chart(df).mark_bar().encode(
    x="",
    y=""
).properties(
    width=700,
    height=300,
)
```

### Scatter plot
```python
alt.Chart(df).mark_point().encode(
    x='',
    y=''
)
```

### Line Chart
```python
alt.Chart(df).mark_line().encode(
    x='',
    y='',
    color=''
).properties(
    width=700,
    height=300,
    title='Graph title'
)
```

# Combining
### Layering
```python
chart1 + chart2
```

### Horizontal Concatenation
```python
chart1 | chart2
```

### Vertical Concatenation
```python
chart1 & chart2
```
