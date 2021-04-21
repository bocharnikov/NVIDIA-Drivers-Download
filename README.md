# NVIDIA-Drivers-Download
Загрузка последнего драйвера для видеокарт от NVIDIA.

Ссылка [https://www.nvidia.ru/Download/driverResults.aspx/172582/ru](https://www.nvidia.ru/Download/driverResults.aspx/172582/ru), а именно **172582** - отвечает за выбор элементов из выпающего списка. Тип продукта, серия продукта, семейство продукта и операционная система формируется здесь: [https://www.nvidia.ru/Download/index.aspx?lang=ru](https://www.nvidia.ru/Download/index.aspx?lang=ru)
В случае необходимости выбор элементов остаётся за вами.

## CRONTAB

```
30 9 * * 0 /root/nvidia.sh
#Каждое воскресенье в 9:30
```

## Поддержка следующих продуктов по умолчанию в скрипте:

**NVIDIA TITAN Series:**

NVIDIA TITAN RTX, NVIDIA TITAN V, NVIDIA TITAN Xp, NVIDIA TITAN X (Pascal), GeForce GTX TITAN X, GeForce GTX TITAN, GeForce GTX TITAN Black, GeForce GTX TITAN Z

**GeForce RTX 30 Series:**

GeForce RTX 3090, GeForce RTX 3080, GeForce RTX 3070, GeForce RTX 3060 Ti, GeForce RTX 3060

**GeForce RTX 20 Series:**

GeForce RTX 2080 Ti, GeForce RTX 2080 SUPER, GeForce RTX 2080, GeForce RTX 2070 SUPER, GeForce RTX 2070, GeForce RTX 2060 SUPER, GeForce RTX 2060

**GeForce 16 Series:**

GeForce GTX 1660 SUPER, GeForce GTX 1650 SUPER, GeForce GTX 1660 Ti, GeForce GTX 1660, GeForce GTX 1650

**GeForce 10 Series:**

GeForce GTX 1080 Ti, GeForce GTX 1080, GeForce GTX 1070 Ti, GeForce GTX 1070, GeForce GTX 1060, GeForce GTX 1050 Ti, GeForce GTX 1050, GeForce GT 1030, GeForce GT 1010

**GeForce 900 Series:**

GeForce GTX 980 Ti, GeForce GTX 980, GeForce GTX 970, GeForce GTX 960, GeForce GTX 950

**GeForce 700 Series:**

GeForce GTX 780 Ti, GeForce GTX 780, GeForce GTX 770, GeForce GTX 760, GeForce GTX 760 Ti (OEM), GeForce GTX 750 Ti, GeForce GTX 750, GeForce GTX 745, GeForce GT 740, GeForce GT 730, GeForce GT 720, GeForce GT 710

**GeForce 600 Series:**

GeForce GTX 690, GeForce GTX 680, GeForce GTX 670, GeForce GTX 660 Ti, GeForce GTX 660, GeForce GTX 650 Ti BOOST, GeForce GTX 650 Ti, GeForce GTX 650, GeForce GTX 645, GeForce GT 640, GeForce GT 635, GeForce GT 630
