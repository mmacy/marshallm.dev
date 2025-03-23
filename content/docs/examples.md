---
title: Examples
description: See your project in action!
date: 2017-01-05
weight: 3
---

{{% pageinfo %}}

This is a placeholder page that shows you how to use this template site.

{{% /pageinfo %}}

Do you have any example **applications** or **code** for your users in your repo
or elsewhere? Link to your examples here.

Normal Markdown-style code fence:

```python
from datetime import datetime

from pydantic import BaseModel, PositiveInt


class User(BaseModel):
    id: int
    name: str = 'John Doe'
    signup_ts: datetime | None
    tastes: dict[str, PositiveInt]
```

Docsy [card shortcode](https://www.docsy.dev/docs/adding-content/shortcodes/#shortcode-card-programming-code) version:

{{< card code=true header="**Python**" lang="Python" >}}
from datetime import datetime

from pydantic import BaseModel, PositiveInt


class User(BaseModel):
    id: int
    name: str = 'John Doe'
    signup_ts: datetime | None
    tastes: dict[str, PositiveInt]
{{< /card >}}

&nbsp;
