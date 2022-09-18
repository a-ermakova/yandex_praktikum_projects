# Описание репозитория
Данный репозиторий содержит проекты, выполненные мной во время прохождения курса "Аналитик данных" от Яндекс Практикума. На данный момент в рамках программы я сделала 11 самостоятельных проектов, однако здесь выложены 8 из них, поскольку остальные выполнялись непосредственно на платформе Яндекс Практикума (отдельные задания в тренажёре по SQL), либо содержали значительный неавторский компонент.

Краткое описание проектов в репозитории (от новых к ранним):
1. **Анализ поведения пользователей мобильного приложения** (папка `app_aab_test`): на основе логов мобильного приложения за определённый период по доставке продуктов питания построила воронку продаж, определила этап с наименьшей конверсией, предложила пути решения данной проблемы. Кроме того, проанализировала результаты A/A/B-теста изменения шрифтов в приложении. *Навыки: A/B-тестирование, визуализация данных, статистический тест.*
2. **Исследование рынка общественного питания в Москве** (папка `moscow_restaurants`): изучив данные о заведениях общественного питания Москвы, дала рекомендации по виду, размеру и месту положения объекта общественного питания, где по задумке гостей обслуживают роботы. Результаты исследования представила в виде презентации. *Навыки: исследовательский анализ данных, визуализация данных, подготовка презентаций.*
3. **Приоритизация гипотез по увеличению продаж и анализ результатов A/B-теста** (папка `ab_test`): провела приоритизацию гипотез, используя фреймворки ICE и RICE. Далее проанализировала результаты A/B-тестирования: построила графики кумулятивных показателей по группам (выручки, среднего чека, конверсии), посчитала статистическую значимость различий конверсий и средних чеков между группами. В результате мною был сделан вывод о необходимости завершения A/B-теста и признания его успешным. *Навыки: фреймворки ICE, RICE, A/B-тест, статистический тест.*
4. **Анализ рекламной кампании развлекательного приложения Procrastinate Pro+** (папка `app_ad_campaign`): проведён когортный анализ, посчитаны основные маркетинговые метрики (LTV, ROI, CAC, Retention Rate, Conversion Rate), проанализированы расходы на рекламу по источникам, выявлены причины убытков компании, даны рекомендации по решению проблемы. *Навыки: исследовательский анализ, анализ бизнес-показателей.*
5. **Интернет-магазин компьютерных игр** (папка `games_research`): на основе исторических данных о продажах и рейтингах компьютерных игр сделан прогноз относительно их популярности в следующем году, а также составлен портрет пользователей по регионам. Опираюсь на эти данные, предоставлены рекомендации по разработке рекламной кампании для Интернета-магазина компьютерных игр "Стримчик". *Навыки: обработка данных, исследовательский анализ, данных, статистический тест, визуализация данных.*
6. **Определение перспективного тарифа для телеком-компании** (папка `mobile_tariffs`): провела анализ поведения клиентов при использовании услуг оператора, определила наиболее популярные услуги, проверила гипотезы о различии выручки абонентов разных тарифов, а также о различии выручки абонентов из Москвы и других регионов. *Навыки: предобработка данных, исследовательский анализ данных, статистический тест, критерий Стьюдента.*
7. **Исследование рынка недвижимости в Санкт-Петербурге** (папка `spb_real_estate`): используя данные Яндекс.Недвижимости, определила параметры, влияющие на стоимость квартир в Санкт-Петербурге и близлежащих населённых пунктах, предварительно предобработав данные и проведя их базовую проверку. *Навыки: обработка данных, категоризация, исследовательский анализ данных, определение зависимостей.*
8. **Исследование надёжности заёмщиков** (папка `solvency_research`): на основе данных кредитного отдела банка исследовано влияние различных факторов на факт своевременного погашения кредита. *Навыки: обработка данных, пропуски, дубликаты, категоризация.*

При выполнении проектов были использованы различные библиотеки. Основные из них - `pandas`, `numpy`, `matplotlib`, `seaborn`.

Поскольку датасеты были предоставлены Яндекс Практикумом и являются интеллектуальной собственностью, все ссылки на учебные данные скрыты.