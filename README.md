# График компетенций

Необходимо реализовать график, отображающий взаимосвязь между компетенциями и связанными навыками.
На внешнем кольце отображаются навыки, на внутреннем - компетенции.
При нажатии на компетенцию, отображаются линии, соединяющие её со связанными навыками.
Линии основных навыков (mainSkills) - оранжевые, дополнительных (otherSkills) - фиолетовые.

## Дизайн

https://www.figma.com/file/b6Vi2BgPs9VpaRp0NJ1RUw/chart-task-design?type=design&node-id=0%3A1&mode=design&t=YcwyItVfKIIvmPaN-1

## Дополнительно 

1. реализовать возможность выбора навыка, и отображения всех связанных с ним компетенций.
1. при выборе компетенции, соответствующие навыки должны располагаться как можно ближе, чтобы исключить длинных пересекающихся между собой линий
1. реализовать анимацию плавной отрисовки соединительных линий

## Демо

![chrome_Pl9cbyDiGg](https://github.com/Cloudo/chart-task/assets/2546209/8e3f49b3-7de1-4a1b-8d30-aba6809996c4)

## Данные
```
[
  {
    name: "Финансовый аналитик",
    mainSkills: ["Excel", "SQL", "VBA", "1С"],
    otherSkills: ["Power BI", "Python"],
  },
  {
    name: "Предприниматель",
    mainSkills: ["1C", "Excel", "Power BI"],
    otherSkills: [
      "Google Analytics",
      "Яндекс.Метрика",
      "Python",
      "SQL",
      "Tilda",
    ],
  },
  {
    name: "Продуктовый дизайнер",
    mainSkills: [
      "Figma",
      "Sketch",
      "Illustrator",
      "Photoshop",
      "Principle",
      "Tilda",
    ],
    otherSkills: ["Shopify", "Protopie", "Cinema 4D"],
  },
  {
    name: "Менеджер проекта",
    mainSkills: [
      "Visio",
      "1C",
      "Google Analytics",
      "Яндекс.Метрика",
      "Python",
      "SQL",
      "Tilda",
    ],
    otherSkills: ["Figma", "Sketch", "Shopify"],
  },
  {
    name: "Финансовый менеджер",
    mainSkills: ["1C", "Excel", "Power BI"],
    otherSkills: ["BPMN"],
  },
  {
    name: "Руководитель финансового департамента компании",
    mainSkills: ["Sketch", "Figma"],
    otherSkills: ["Shopify", "HQL"],
  },

  {
    name: "Продуктовый аналитик",
    mainSkills: [
      "Google Analytics",
      "Яндекс.Метрика",
      "SQL",
      "Power BI",
      "Python",
      "Excel",
    ],
    otherSkills: ["HQL", "Tableau", "R", "Machine learning"],
  },

  {
    name: "Руководитель финансового продукта",
    mainSkills: ["Visio"],
    otherSkills: ["Python"],
  },
  {
    name: "Менеджер по маркетингу",
    mainSkills: [
      "Google Analytics",
      "Яндекс.Метрика",
      "Google Ads",
      "Ahrefs",
      "Главред",
      "My Target",
    ],
    otherSkills: ["Tilda", "Photoshop", "Xenu", "Python"],
  },

  {
    name: "Менеджер по цифровой трансформации",
    mainSkills: [
      "Visio",
      "Google Analytics",
      "Яндекс.Метрика",
      "Python",
      "SQL",
      "Tilda",
    ],
    otherSkills: ["Figma", "Sketch", "Shopify"],
  },
]
```
