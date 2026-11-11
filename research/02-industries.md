# 02. Боли отраслей Казахстана, которые можно атаковать софтом

Ресерч 11.11.2026. Пометки по каждой цифре: **[проверено]** — страница открыта и прочитана; **[сниппет]** — цифра видна только в поисковой выдаче, перед слайдами её надо открыть и перепроверить. Цифры без рабочей ссылки сюда не попали.

Команде важно: в слайды идут только цифры, которые кто-то из команды сам открыл и прочитал в первоисточнике.

## Шорт-лист

Ранжирование — моя оценка: тяжесть боли в цифрах × посильность для команды без железа × доступность данных × слабость конкурентов.

| # | Отрасль | Боль | Цифры | Данные для MVP | Кто уже делает |
|---|---|---|---|---|---|
| 1 | Строительство | Нарушения на площадке и в документах находят поздно, штрафы и переделки | 1463 нарушения в Астане и Алматы за 2025 [сниппет, [newtimes.kz](https://newtimes.kz/vlast/224863-pochti-1500-narushenii-na-stroikakh-astany-i-almaty-chto-otvetili-v-pravitelstve)]; штрафы застройщикам 1,59 млрд ₸, 3 тыс.+ внеплановых проверок [сниппет, [finratings.kz](https://finratings.kz/news/12112-kazakhstanskikh-zastroishchikov-oshtrafovali-na-1-59-mlrd-tenge/)]; госпилот с компьютерным зрением сокращает поиск несоответствий с 3 дней до 4 часов [проверено, [zakon.kz](https://www.zakon.kz/obshestvo/6516118-v-kazakhstane-ii-budet-proveryat-stroyki-i-vyyavlyat-narusheniya-za-4-chasa.html)]; объём стройработ за 2025 — 10,8 трлн ₸ по оценке Freedom Broker [сниппет, [kapital.kz](https://kapital.kz/economic/151326/stroitelnaya-otrasl-kazahstana-vyhodit-na-novyj-etap-razvitiya.html)] | Нормы публичны (adilet.zan.kz); открытые датасеты по СИЗ и стройплощадкам есть, местных фото нарушений нет | Armeta — экспертиза проектной документации, контракт с Госэкспертизой [проверено, [digitalbusiness.kz](https://digitalbusiness.kz/2026-08-07/startap-iz-kazahstana-vnedrit-iskusstvenniy-intellekt-v-gosekspertizu-stroitelstva-po-vsey-strane/)]; AI Qurylys / AI Baqylau — платформа из шести модулей, видеоаналитика СИЗ через камеры [проверено, [aibaqylau.kz](https://aibaqylau.kz/)]; государственный E-Qurylys |
| 2 | Сельское хозяйство | Болезни и вредители определяются поздно | Цель — цифровизация 50% пашни к 2028 [сниппет, [bizmedia.kz](https://bizmedia.kz/2025-10-20-ohvatit-czifrovoj-transformacziej-ne-menee-50-selhozugodij-v-kazahstane-planiruet-kabmin/)]. Ущерб от вредителей в тенге не найден | PlantVillage — общий, не под местные культуры | Госпрограмма «ИИ-помощник фермера» |
| 3 | Финтех | Интернет-мошенничество и дропперы | 26,3 тыс. дел за 2025, +86,1% [сниппет, [npck.kz](https://npck.kz/?p=36791)]; 700+ дел по дропперству [сниппет, [dknews.kz](https://dknews.kz/en/articles-in-english/374933-digital-fraud-in-kazakhstan-new-data-key-schemes-and)] | Транзакций в открытом доступе нет | Антифрод-центр Нацбанка, банки |
| 4 | Телеком | Жалобы абонентов | ~2,6 тыс. жалоб за 2025, +17,7%; штрафы 314,6 млн ₸ [проверено, [kapital.kz](https://kapital.kz/gosudarstvo/152034/chto-ne-ustraivaet-kazahstancev-v-uslugah-svyazi.html)] | Тексты жалоб закрыты | Операторы сами. Объём жалоб мал относительно выручки — слабый кейс |
| 5 | Здравоохранение | Нехватка врачей в регионах, скрининг | 5 743 новых случая рака молочной железы за 2025 [сниппет, [24.kz](https://24.kz/ru/news/zdravookhranenie/799556-v-kazakhstane-bolee-17-tysyach-sluchaev-raka-grudi-vyyavili-na-rannikh-stadiyakh)] | Данные пациентов — персональные; медицинское ПО требует регистрации | Региональные ИИ-скрининги, Cerebra |
| 6 | Энергетика | Аварийность и износ ТЭЦ | Цифры в источниках расходятся, ссылки не сохранились | Телеметрия закрыта | Не найдено |
| 7 | Горнодобывающая | Простои техники | 65 компаний уже используют ИИ [сниппет, [inbusiness.kz](https://www.inbusiness.kz/ru/last/65-kompanij-gornodobyvayushej-otrasli-kazahstana-vnedrili-ii)]. Потери в тенге не найдены | Данные закрыты | Вендоры MES |
| 8 | Образование | Нехватка учителей | 5 357 вакансий [сниппет, [inform.kz](https://www.inform.kz/ru/shkolam-kazahstana-ne-hvataet-bolee-5-tisyach-pedagogov-2ad1cec2)] | — | ИИ вакансии не закрывает; ИИ-репетиторы перегреты (см. `03`) |

Вывод: по сочетанию «есть цифры, есть плательщик, данные публичны, ИИ действительно нужен» лидирует строительство. Оно же самое занятое — там уже работают Armeta и AI Qurylys, и государство строит свой контроль. Спрос это подтверждает, но клин надо выбирать узкий.

## Охрана труда — дополнительные цифры к строительству

- 2328 несчастных случаев, связанных с трудовой деятельностью, за 2025 год по всем отраслям, −5,8% к 2024 [сниппет, [stat.gov.kz](https://stat.gov.kz/ru/news/o-travmatizme-svyazannom-s-trudovoy-deyatelnostyu/)].
- 188 погибших на производстве за год [сниппет, [bizmedia.kz](https://bizmedia.kz/2026-06-02-v-kazahstane-za-god-na-proizvodstve-pogibli-188-rabotnikov/)].
- Разбивка по строительству есть в таблицах Бюро нацстатистики по видам деятельности, но я её не открывал.

## Регулирование и «в русле стратегии»

Все пункты ниже — [сниппет], даты в источниках местами расходятся.

- Закон «Об искусственном интеллекте» № 230-VIII: подписан 17.11.2025, в силе с 18.01.2026. Риск-ориентированный подход, маркировка ИИ-контента ([mondaq.com](https://www.mondaq.com/new-technology/1735592/the-new-artificial-intelligence-law-of-the-republic-of-kazakhstan)).
- Цифровой кодекс № 255-VIII от 09.01.2026, в силе с июля 2026 ([kapital.kz](https://kapital.kz/gosudarstvo/150445/cifrovoj-kodeks-chto-izmenilos-dlya-grazhdan-i-biznesa.html)).
- Персональные данные: закон № 94-V с поправками 2026 года ([morganlewis.com](https://www.morganlewis.com/ru/pubs/2026/07/republic-of-kazakhstan-data-protection-law-amendments-in-2026)). Фото людей на стройке — персональные данные, нужно согласие или размытие лиц.
- План цифровизации стройотрасли на 2026–2027 утверждён 09.01.2026 ([digitalbusiness.kz](https://digitalbusiness.kz/2026-03-10/vse-stroitelnie-gosuslugi-teper-dostupni-onlayn-a-sami-stroyki-kontroliruet-ii/amp/)).
- Казахские LLM: AlemLLM (веса на Hugging Face закрыты, [astanahub/alemllm](https://huggingface.co/astanahub/alemllm)), KazLLM от ISSAI. Конкурировать на уровне базовой модели бессмысленно, брать как компонент.
- Открытые данные: [data.egov.kz](https://egov.kz/cms/ru/articles/open-data), более 3 тыс. наборов.

## Что не исследовано

Робототехника, медиа, кибербезопасность, операционная автоматизация; регистрация медицинского ПО; национальные потери в энергосетях; число строительных компаний и организаций технадзора в Казахстане (нужно для расчёта рынка).
