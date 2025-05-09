# AI Labs
## Чубуков Андрей Владимирович М8О-408Б-21

Лабораторные работы 6-8 по курсу "Методы, средства и технологии мультимедиа"

*Файл с 7 лр открывается только в google colab

## Датасеты

- https://www.kaggle.com/datasets/sujaykapadnis/smoking

## Подведение итогов / сравнение результатов

Таблица с результатами работы каждого алгоритма.

### Метрики:

- Accuracy
- IoU

## Результаты

<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">Сверточные нейронные сети (CNN) - torchvision</td>
        <td>Классификация</td>
        <td>0.73</td>
        <td>0.88</td>
        <td>0.84</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.80</td>
        <td>0.83</td>
        <td>0.73</td>
    </tr>
    <tr>
        <td rowspan="2">UNet (segmentation_models.pytorch)</td>
        <td>Классификация</td>
        <td>0.91</td>
        <td>0.95</td>
        <td>0.79</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.71 (UNet-ResNet34)</td>
        <td>0.82 (UNet-ResNet34)</td>
        <td>0.79</td>
    </tr>
    <tr>
        <td rowspan="2">YOLO (Ultralytics)</td>
        <td>Классификация</td>
        <td>0.87</td>
        <td>0.91</td>
        <td>0.8</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.74</td>
        <td>0.80</td>
        <td>0.72</td>
    </tr>
</table>
