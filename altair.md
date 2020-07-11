# Chuleta de Altair

## Import in python
```
import pandas as pd
import altair as alt
```
## Bar Chart
```
alt.Chart(brain).mark_bar().encode(
    x="",
    y=""
)
```
## Scatter plot
```
alt.Chart(brain).mark_point().encode(
    x='',
    y=''
)
```
## Line Chart
```
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
