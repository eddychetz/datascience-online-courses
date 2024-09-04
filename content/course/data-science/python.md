---
title: Import Data
date: '2024-09-04'
type: book
weight: 20
---

Build a foundation in Python by learning how to import data into your workspace.

<!--more-->

{{< icon name="clock" pack="fas" >}} 1-2 hours per week, for 8 weeks

## Learn

{{< youtube rfscVS0vtbw >}}

## Quiz

{{< spoiler text="Import data from CSV or excel file etc using pandas?" >}}

CSV

```python
import pandas as pd
file_path = '.../.../yourfile.csv'
csv_df = pd.read_csv(file_path)
csv_df.head()
```

excel

```python
import pandas as pd
file_path = '.../.../excel_file.xlsx'
excel_df = pd.read_excel(file_path)
excel_df.head()
```

## Learn more

{{< spoiler text="How to import data from github?" >}}
Open the file location on GitHub, `view raw` and copy the link into clipboard.
```python
github_filepath = 'raw_link_copied.csv'
github_df = pd.read_csv(github_filepath)
github_df.head()
```
{{< /spoiler >}}
