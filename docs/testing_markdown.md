# Testing Markdown :rainbow:

Here I'm going to test Markdown installed on my laptop.

Testing bullet list:

* Item
* Item
* Item

Testing ordered list:

1. Item
1. Item
1. Item

How about making a word **bold**.

Table, anyone?

|Column 1|Column 2|
|--------|--------|
|LOL     |LOL     |

A here's a link to the [Home Page](index.md).

A slice of code, maybe?

``` yaml
python:
  version: 3.7
  install:
    - requirements: docs/requirements.txt
```

```php
<?php echo 'Hello, World!'; ?>
```

And for dessert, a single code phrase, for instance, `python.version`.

``` py
import tensorflow as tf
```


## Testing Extensions

Code snippet with the file name:

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]: # (1)
                items[j], items[j + 1] = items[j + 1], items[j] # (2)
```

1.  LOL
2.  LOL2

Code snippet with an annotation:

``` yaml
theme:
  features:
    - content.code.annotate # (1)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

## Grouping Code Blocks

Testing Content tabs

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

=== "C+++"

    ``` c++
    #include <iostream>
    ```
