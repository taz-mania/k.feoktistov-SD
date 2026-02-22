Проектирование "Сервиса запросов информации о наличии товаров на полках в режиме реального времени (API определения наличия товаров на полках)"

В составе проекта представлены следующие артефакты:

* [Архитектурное решение](./architecture-decision.adoc)

* [Отчеты о выполнении ДЗ и проекта](./Отчет.adoc)

Используется формат описания MarkDown

Рендер в pdf:

```
docker run --rm -v "$(pwd):/data" pandoc/latex:alpine \
   sh -c "find /data -name '*.md' | sort | \
   pandoc -f markdown -t pdf -o /data/Архитектурное_решение.pdf \
   --pdf-engine=xelatex --toc -V geometry:margin=2.5cm"
```
