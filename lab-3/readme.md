# Cегментация 

**Исполняемый файл** segmentation.py

**Параметры**
- -path - путь к изображению
- -method - метод сегментации (split, merge, combined)
- -i - коэфицент момента
- -j - коэфицент момента

**Вывод**
* ./output/moments.txt - файл содержащий вычесленные моменты для каждоого сегмента

**Примечания**
* combined - метод, при котором изображения сначала разбивается (split) на сегменты, которые потом сливаются (merge)
* При использовании метод merge рекомендуются использоваться только на малых изображениях в веду его низкой скорости работы
