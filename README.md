# Marketing Campaign Spend Analysis (Power BI Dashboard)

## English

**Business Problem:** A company’s marketing team needed to analyze advertising spend across multiple channels (e.g. internet, outdoor, TV, radio) and understand how these investments translated into revenue. Key questions included how the budget was distributed by channel, which channels yielded the highest revenue and net revenue, and which marketing channels delivered the best return on investment.

**Solution:** Developed an interactive Power BI dashboard to visualize advertising spend vs. outcomes. Using Power Query for data cleansing and preparation, the raw budget data (Excel source) was cleaned (e.g. removed records with missing IDs and standardized product names). A date dimension was added for time-based analysis. In Power BI, DAX measures were created to calculate total revenue, net revenue (profit), and ROI metrics. The dashboard includes KPI cards displaying total revenue and net revenue, bar charts showing spend by channel, and detailed tables with filters for deeper exploration. Categories were custom-sorted (e.g. Internet → Outdoor → TV, etc.) to match business context. The data model was designed for ease of slicing and drilling down into each channel’s performance.

**Tools Used:** Power BI Desktop, Power Query, DAX, Excel.

**Value Delivered:** This project provided marketing and finance stakeholders with a clear view of advertising efficiency across channels. The dashboard quickly highlights which channels are under- or over-performing by comparing spend to revenue, allowing decision-makers to reallocate marketing budget toward the most profitable channels.

---

## Русский

**Задача:** Команде маркетинга было необходимо проанализировать рекламные расходы по нескольким каналам (интернет, наружная реклама, ТВ, радио) и понять, как эти инвестиции влияют на выручку. Важно было определить, как распределён бюджет по каналам, какие из них приносят наибольшую выручку и прибыль, и где ROI (окупаемость) максимален.

**Решение:** Я разработал интерактивный дашборд в Power BI, который визуализирует соотношение затрат и результата. С помощью Power Query данные из Excel были очищены (удалены строки с пропущенными ID, стандартизированы наименования продуктов). Добавлена дата-таблица для анализа во времени. В Power BI созданы DAX-меры для расчёта выручки, прибыли и ROI. Дашборд включает KPI-индикаторы по выручке и прибыли, диаграммы по каналам, таблицы с фильтрами. Порядок каналов настроен вручную (например: Интернет → Наружка → ТВ и т.д.) для бизнес-логики. Модель данных адаптирована для срезов и drill-down по каналам.

**Инструменты:** Power BI Desktop, Power Query, DAX, Excel.

**Ценность:** Данный проект дал отделам маркетинга и финансов наглядное представление об эффективности рекламы. Визуализация быстро показывает, какие каналы перерасходуют бюджет или дают наибольшую отдачу, что позволяет оптимально перераспределить затраты и повысить рентабельность кампаний.

