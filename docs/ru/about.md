# О LogiCore Platform

**LogiCore Platform (LCP)** — это единая информационная платформа управления операционными процессами компании.


**LCP применим:**
* в логистике: планирование и исполнение перевозок, управление транспортными средствами и подрядчиками, контроль маршрутов и сроков;
* на складах: управление приёмкой, размещением, хранением, комплектацией и отгрузкой товарно-материальных ценностей (ТМЦ);
* в мерчендайзинге: организация и контроль полевых работ по монтажу, обслуживанию и демонтажу оборудования у клиентов;
* в управлении: формирование финансовых документов, аналитика KPI, документооборот и коммуникация между участниками процессов (сотрудниками, подрядчиками и клиентами).

## Основные модули

![_modules_about](_images/_modules_about.png){.center width=1200}

::: page-constructor
render: true
blocks:
  - type: 'card-layout-block'
    title: 'Основные модули'
    colSizes:
      all: 12
      md: 4
      sm: 6
    indent:
      top: sm
    children:
      - type: 'layout-item'
        content:
          title: 'Transport Integration Core (TIC)'
          text: 'Сквозное управление перевозками, мониторинг трейсов, API интеграция с перевозчиками.'
        media:
          image: 'https://storage.yandexcloud.net/diplodoc-www-assets/pages/index-diplodoc/ddos-index-item-01-01.png'
          disableCompress: true
        fullScreen: true
        border: true
        disableCompress: true
      - type: 'layout-item'
        content:
          title: 'Space Lifecycle Core (SLC)'
          text: 'Система управления пространствами распространяется за пределы привычного понимания WMS, так как учитывает не только классические принципы складского учета, но и позволяет контролировать пространства и цифровые транзакции движения объектов сервиса.'
        media:
          image: 'https://storage.yandexcloud.net/diplodoc-www-assets/pages/index-diplodoc/ddos-index-item-01-02.png'
          disableCompress: true
        fullScreen: true
        border: true
        disableCompress: true
      - type: 'layout-item'
        content:
          title: 'POSM Lifecycle Core (PLC)'
          text: 'Центральный микросервис, отвечающий за жизненный цикл «цифрового двойника» POSM-актива'
        fullScreen: true
        border: true
        disableCompress: true
:::

## Готовые функциональные блоки продукта

1. Пользователи и контрагенты 
2. Договоры и поручения
3. Справочники (Конфигураторы)
├── Номенклатура 
└── Пространства
4. Заказ
├── Создание заказа в мануальном режиме или через exсel-шаблон
└── Планирование и мониторинг заказа на диаграмме Ганта или в недельном представлении календаря
5. Заявки на склад (система документооборота)
├── Поступление
├── Списание
└── Проведение документов