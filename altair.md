# Chuleta de Altair

## Import
```python
import pandas as pd
import altair as alt
```

## Bar Chart
```python
alt.Chart(brain).mark_bar().encode(
    x="",
    y=""
).properties(
    width=700,
    height=300,
)
```

## Scatter plot
```python
alt.Chart(brain).mark_point().encode(
    x='',
    y=''
)
```

## Line Chart
```python
alt.Chart(trends).mark_line().encode(
    x='',
    y='',
    color=''
).properties(
    width=700,
    height=300,
    title='Graph title'
)
```
