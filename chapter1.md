---
title: 'Data Loading'
description: 'Import CSV Data'
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

This is an example exercise. The aim is to load data and analyze times series.

`@instructions`
List all the variable with list() function.
Load csv file.
plot data.

`@hint`


`@pre_exercise_code`
```{r}
global_temp <- read.csv("DAX_2019-04-12.csv")
global_temp.info()
plot(global_temp)
ls()


```

`@sample_code`
```{r}

```

`@solution`
```{r}


```

`@sct`
```{r}

```
