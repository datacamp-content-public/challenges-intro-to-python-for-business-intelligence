---
title: "example_python_challenges"
output: html_document

--- type:MultipleChoiceChallenge key:115qFYuQ4pPlifqZze0QkDORLwVufanGIfC difficulty:1
## Choose the right answer

*** =assignment1
Which command explicitly imports the `pyplot` subpackage from `matplotlib`?

*** =options1
- `import matplotlib as pyplot`
- `import pyplot from matplotlib`
- [`import matplotlib.pyplot as plt`]
- `from pyplot import plt`
- `import pyplot as plt`

*** =assignment2
Assuming `matplotlib.pyplot` is imported as `plt`, which command displays the current figure?

*** =options2
- `matplotlib.pyplot.show()`
- `matplotlib.show()`
- `pyplot.show()`
- `plt.show`
- [`plt.show()`]


*** =assignment3
Assuming `matplotlib.pyplot` is imported as `plt`, which command clears the current figure?

*** =options3
- `matplotlib.pyplot.clear()`
- `plt.clear()`
- `plt.clf`
- `plt.clear`
- [`plt.clf()`]

--- type:BlanksChallenge key:8a565a9166
## concatenating lists

*** =pre_challenge_code
```{python}
import dccpu.generators as g
```

*** =code
```{python}
l1 = {{l1}}
l2 = {{l2}}
print(l1 {{_op}} l2)
```

*** =variables
l1:
  - '!expr g.int_vector()'
l2:
  - '!expr g.int_vector()'
op:
  - '+'
  
--- type:OutputChallenge key:6258197972
## popping lists (2)

*** =pre_challenge_code
```{python}
import dccpu.generators as g
```

*** =code
```{python}
l1 = {{$l1}}
p = l1.pop()
print(p)
```

*** =code2
```{python}
l1 = {{$l1}}
p = l1.pop({{n}})
print(p)
```

*** =variables
l1:
  - '!expr g.int_vector(size=6)'
n:
  - '!expr g.rand_int(hi=5)'
  

