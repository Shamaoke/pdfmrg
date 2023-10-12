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

# Examples #

````
pdfmrg \
  -p:t '„Yale language series“' \
  -p:n 2 \
  -p:w 182.0 \
  -p:h 257.0 \
  -t:w 37.82 \
  -t:h 2.02
#
# „Yale language series“, с. 2
# ----
# Ширина: 182.0 мм
# Высота: 257.0 мм
# ----
# Верхняя: 127.49 мм
# Правая: 109.91 мм
# Нижняя: 129.51 мм
# Левая: 72.09 мм
#
````

