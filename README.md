**pdfmrg**

````
pdfmrg -p:t PAGE_TITLE -p:n PAGE_NUMBER -p:w PAGE_WIDTH -p:h PAGE_HEIGHT -t:w TEXT_WIDTH -t:h TEXT_HEIGHT
````

Calculate margins for pages of PDF documents.

# Options #

**-p:t**

  Specify a page heading.

**-p:n**

  Specify a page number.

**-p:w**

  Specify page width.

**-p:h**

  Specify page height.

**-t:w**

  Specify text block width.

**-t:h**

  Specify text block height.

**-c:s**

  Specify page cutting size.

# Examples #

````
pdfmrg \
  -p:t '„Yale language series“' \
  -p:n 'с. 3' \
  -p:w 182.0 \
  -p:h 257.0 \
  -t:w 37.82 \
  -t:h 2.02 \
  -c:s 3.0
#
# „Yale language series“, с. 3
#   ----
#   Страница
#   ----
#   Ширина: 182.00 мм
#   Высота: 257.00 мм
#   ----
#   Текст
#   ----
#   Ширина: 37.82 мм
#   Высота:  2.02 мм
#   ----
#   Границы текст
#   ----
#   Верхняя: 127.49 мм
#   Правая:  109.91 мм
#   Нижняя:  129.51 мм
#   Левая:    72.09 мм
#   ----
#   Размер обрезки: 3.00 мм
#   ----
#   Границы обрезка
#   ----
#   Верхняя: 124.49 мм
#   Правая:  112.91 мм
#   Нижняя:  132.51 мм
#   Левая:    69.09 мм
#
````

