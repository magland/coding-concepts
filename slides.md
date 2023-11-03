---
marp: true
paginate: true
theme: magland-theme
# header: <img src="https://user-images.githubusercontent.com/3679296/276917690-ed331783-4853-44ea-969f-b29d9415d21d.png" style="margin-left:15px" width="200px" />
footer: <div>Coding Concepts</div>
---

<!-- For using custom theme, see https://github.com/orgs/marp-team/discussions/115 -->

# Miscellanous Coding Concepts

<br >
<br >
<br >

by Jeremy Magland

Updated November 2023

---

# The difference between installing packages and using packages in Python and R

Have you ever wondered what is the difference between the following two commands?

```bash
pip install numpy

import numpy as np
```

or in R

```r
install.packages('ggplot2')

library(ggplot2)
```

---

## Making a delicious dinner (two steps)

![bg right:45% 80%](https://user-images.githubusercontent.com/3679296/280300033-833f0131-307e-4e5f-b103-e3f726c4e116.png)

### Step 1: Acquire the ingredients from the store and "install" them in your refrigerator or pantry.
- You only need to do this once.
- This is like installing a package on your computer.
- The store is like PyPI (Python) or CRAN (R).
- You may or may not use it right away.
- But you have it in case you need it.

---

## Making a delicious dinner (two steps)

<!-- https://www.pexels.com/photo/bowl-with-a-salad-of-lettuce-and-strawberries-15733224/ -->
![bg right:45% 80%](https://user-images.githubusercontent.com/3679296/280302315-5518d325-ec5b-4cde-816e-60739f0544e7.jpg)

### Step 2: Use the ingredients to make your dinner.

- This is like using a package in your code.
- You may use it many times.
- You may use it in different recipes.
- You may use it in different ways.
- You may use it with other ingredients.

---

## When you install a package, where does it go?

<!-- https://www.flickr.com/photos/goedekers/12640052475 -->
![bg right:45% 80%](https://user-images.githubusercontent.com/3679296/280303112-e918d33c-16e8-49e5-a3c9-5992c1b26cf2.jpg)

- Python: `pip install numpy` installs the package in a directory like `/usr/local/lib/python3.8/site-packages/numpy`
- R: `install.packages('ggplot2')` installs the package in a directory like `/usr/local/lib/R/site-library/ggplot2`
- In short: it gets stored ON DISK!

---

## When you use a package, where does it go?

<!-- https://www.flickr.com/photos/daveynin/3145651657 -->
![bg right:45% 80%](https://user-images.githubusercontent.com/3679296/280303894-b1299f66-f8ef-41b1-bd2a-cfdcab783e01.jpg)

- Python: `import numpy as np` makes the package available in your Python session.
- R: `library(ggplot2)` makes the package available in your R session.
- In short: it gets stored IN MEMORY!

---

## Why is there a difference between install and use?

- We don't want to have to go to the grocery store every time we want to make dinner (although sometimes it seems like we do!)
- We don't want to have to re-download the package every time we use it.
- We don't want the code to have to specify the location of the package.

---

## Differences between how Python and R install packages

- In Python the install command is in the command line (outside of Python)
- In R the install command is in the R console (inside of R)

Which is better? It depends on your perspective. But I think the Python way is better. :)

---

## Thank you!