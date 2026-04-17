# Seedance Video Prompt v1.0 — Original

> Оригинальный промпт для генерации видео через Seedance.
> Общая оценка: **3.6 / 10**

---

## Сценарий (русский, сырой)

```
0:00–0:02
Уставший мужчина 35+ сидит на диване, вокруг серые тона, плечи опущены, 
пустой взгляд в пол, вокруг усталость негатив и на кричит жена 
и как будто картизол АТАКУЕ

0:02–0:04
Он стоит серый мужчина начинает рычать и злиться топай ногой по полу

0:04–0:07
Открывает банку с референса достает таблетку и глотает её
Динамичная трансформация: камера облетает его по спирали, одежда меняется на 
спортивную, поза становится уверенной, появляется лёгкая мускулатура, 
фон взрывается энергетическими волнами

0:07–0:10
Сплит-экран из трёх сцен: слева он поднимает штангу с лёгкостью, 
в центре уверенно ведёт переговоры в офисе, справа танцует с женой на кухне — 
она смеётся, он кружит её

0:10–0:12
Все три сцены сливаются в одну, мужчина стоит на вершине стилизованной горы, 
за спиной восходит солнце, поза победителя с поднятыми руками

0:12–0:14
Плавный переход к упаковке продукта, она вращается в 3D, 
вокруг летают иконки: молния, гиря, сердце, часы — 
капсула-маскот подмигивает и показывает большой палец

Финальный кадр: логотип, упаковка, крупный CTA-баннер с текстом, кнопка пульсирует
```

## Стилевой промпт (английский)

```
Modern 2D vector animation, vibrant saturated colors with orange-gold-teal palette, 
smooth character animation with dynamic camera movements, 
adult male character 35-40 years old with relatable everyman design, 
exaggerated expressive poses, motion graphics elements like energy waves and particle effects, 
clean geometric backgrounds with gradient transitions, 
product mascot as friendly anthropomorphic capsule character, 
cinematic lighting with rim lights and glows, 
social media vertical 9:16 format, high energy pacing with snappy transitions, 
contemporary flat design aesthetic mixed with subtle 3D depth, 
inspirational uplifting mood
```

---

## Оценка по 10 измерениям

| # | Измерение | Балл | Критическая проблема |
|---|---|---|---|
| 1 | Character Consistency | 3 | Нет фиксированных черт — персонаж «дрейфует» между кадрами |
| 2 | Camera Directives | 4 | Только 1 явная директива (спираль), остальные кадры без lens/angle |
| 3 | Lighting Specificity | 3 | Общая фраза «cinematic lighting» без per-scene разбивки |
| 4 | Scene Transitions | 2 | Переходы не описаны как директивы для модели |
| 5 | Style Coherence | 4 | Противоречие: 2D vector + 3D rotation + flat + subtle 3D depth |
| 6 | Action Clarity | 5 | «Кортизол атакует», «рычать и злиться» — модель не знает как визуализировать |
| 7 | Color Progression | 6 | Арка grey→vibrant заявлена, но не захореографирована по кадрам |
| 8 | Technical Specs | 5 | 14с одним промптом нестабильно для Seedance, нет fps/resolution |
| 9 | Audio Cues | 1 | Отсутствуют полностью |
| 10 | Product/Brand Details | 3 | «Банка с референса» — референс не передаётся модели |

**Среднее: 3.6 / 10**

## Основные проблемы

### Опечатки и грамматика
- «картизол АТАКУЕ» → кортизол атакует
- «на кричит жена» → на него кричит жена
- «топай ногой» → топает ногой
- «Он стоит серый мужчина начинает рычать» — несогласованное предложение

### Логические противоречия
- 2D vector + 3D product rotation (разные визуальные языки)
- «Лёгкая мускулатура появляется» за 3 секунды — нефизично
- Жена «кричит» в начале, затем «смеётся и танцует» без арки примирения

### Перегруженные сцены
- 0:04–0:07 (3 сек): 7+ событий (банка, таблетка, глотание, спираль, смена одежды, поза, мускулатура, энерговолны)
- 0:12–0:14 (2 сек): 8+ элементов (упаковка, 4 иконки, маскот, лого, CTA, пульс кнопки)

### Отсутствуют
- Negative prompts (no photorealism, no text artifacts, no character drift)
- Character sheet для консистентности
- Per-shot lighting с указанием color temp
- Audio/music cues для ритма
- Brand placeholders ([BRAND], [CTA_TEXT])
