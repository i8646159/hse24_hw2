# hse24_hw2
### Выполнила Михайлова Ирина Александровна, группа 2.

В задании дано, что наша бактерия из Баренцева моря относится к виду *Thalassolituus oleivorans* (назовем ее, например, *T. oleivorans Barents*). Известен геном другого штамма этого вида бактерий с берегов Сицилии, Италия (*T. oleivorans MIL-1* – http://www.ncbi.nlm.nih.gov/nuccore/HF680312 ). Поэтому будем давать имена генам и белкам нашей бактерии схожие с теми, что были использованы для генов и белков двух других штаммов.

Выполним работу локально в Google Collab ноутбуке (по [ссылке](https://colab.research.google.com/drive/1M98NaMVHA8IOFU4lwjmegpcvt5jwy7g_?usp=sharing)).

**Полученные данные:**
* Предсказано генов: **3705**
* Из них с помощью сравнения с бактерией MIL-1 удалось аннотировать: **124**
  * Это означает, что эти 124 гена, вероятно, кодируют белки с известными функциями, так как они похожи на соответствующие гены в геноме *MIL-1*.
* Количество белков, оставшихся без аннотации функции: **402**
  * Это примерно 11% генома, довольно много. Причин такого большого количества неаннотированных генов может быть несколько:
    * Эти гены могут кодировать новые белки, не имеющие аналогов у других организмов.
    * Они могут иметь функции, специфичные для *T. oleivorans Barents*, и поэтому не были обнаружены в геноме *MIL-1*.
    * Возможные ошибки в предсказании генов или аннотации.
* Процентное соотношение сходства между соответствующими рРНК:
  * Результаты сравнения rRНК показывают высокую степень сходства между геномами *T. oleivorans Barents* и *MIL-1*, что подтверждает родственность сравниваемых бактерий и их сходную генетическую основу.
```
Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_101_length_481_cov_130.204225  percents : ['99%'] 

For seq = NODE_84_length_631_cov_2.064236  percents : ['79%', '88%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_36_length_2725_cov_1.846816  percents : ['80%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_20_length_75280_cov_72.810090  percents : ['100%'] 

For seq = NODE_7_length_192242_cov_65.503624  percents : ['100%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['98%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_36_length_2725_cov_1.846816  percents : ['80%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['99%'] 

For seq = NODE_101_length_481_cov_130.204225  percents : ['100%'] 

For seq = NODE_84_length_631_cov_2.064236  percents : ['79%', '88%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_20_length_75280_cov_72.810090  percents : ['100%'] 

For seq = NODE_7_length_192242_cov_65.503624  percents : ['100%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_36_length_2725_cov_1.846816  percents : ['80%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['99%'] 

For seq = NODE_101_length_481_cov_130.204225  percents : ['100%'] 

For seq = NODE_84_length_631_cov_2.064236  percents : ['79%', '88%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_20_length_75280_cov_72.810090  percents : ['100%'] 

For seq = NODE_7_length_192242_cov_65.503624  percents : ['100%'] 

Resemblance rRna 341494...343033
For seq = NODE_34_length_5050_cov_142.283684  percents : ['100%'] 

For seq = NODE_36_length_2725_cov_1.846816  percents : ['80%']
```
