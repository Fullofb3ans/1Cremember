# 1C remember

'http://127.0.0.1:8000/menu

[
  "ОГЛАВЛЕНИЕ",
  "СОЗДАНИЕ ПАРТНЕРА И КОНТРАГЕНТА",
  "ЗАКАЗ КЛИЕНТА",
  "ДОГОВОР"
]

'http://127.0.0.1:8000/search_by_name/%D0%B4%D0%BE%D0%B3%D0%BE%D0%B2%D0%BE%D1%80'

[
  {
    "id": 22,
    "name": "ДОГОВОР",
    "text": "Договор клиента можно создать в карточке Партнера по ссылке Договоры:",
    "img": "/imgs/3_1.jpg"
  },
  {
    "id": 23,
    "name": "ДОГОВОР",
    "text": "В полях Номер, Дата, Наименование договора необходимо указывать реальные данные. Не допускается указание произвольных значений.\nОрганизация и Счет организации – обязательно проверяем, т.к. эти реквизиты попадают в печатную форму документов. Счет организации обязательно выбираем тот, который указан в договоре с заказчиком",
    "img": "/imgs/3_2.jpg"
  },
  {
    "id": 24,
    "name": "ДОГОВОР",
    "text": "По ссылке Файлы для юристов необходимо прикрепить скан-копию договора.\nДалее договор согласовывается с юристами.",
    "img": "/imgs/3_3.jpg"
  }
]

'http://127.0.0.1:8000/search_by_text/%D0%B4%D0%BE%D0%B3%D0%BE%D0%B2%D0%BE%D1%80'

[
  {
    "id": 7,
    "name": "СОЗДАНИЕ ПАРТНЕРА И КОНТРАГЕНТА",
    "text": "На четвертом шаге помощника:\n-\tОтрасль компании – обязательно нужно заполнить, в разрезе этих данных формируются многие отчеты.\n-\tПоле Основание (договор) не обязательно к заполнению\n-\tФлаг Проектный институт - КО не устанавливают.",
    "img": "/imgs/1_6.jpg"
  },
  {
    "id": 11,
    "name": "ЗАКАЗ КЛИЕНТА",
    "text": "В шапке обработки указывается:\n-\tОрганизация – организация—продавец, указанная в договоре и/или спецификации\n-\tПартнер ВАЖНО! Выбирать того партнера, которому будет производиться отгрузка. Если в карточке Партнера нет Визы клиента и нет возможности его выбрать в заказе, то в комментариях в заказе нужно указать наименование и ИНН верного контрагента. \n-\tСоглашение – Типовое соглашение по договорам или Предоплата 100%. При необходимости в заказе клиента его можно поменять.\n-\tСклад продажи – склад или группа складов, с которых в дальнейшем будет оформлена отгрузка.\nВ верхней табличной части обработки осуществляется поиск товара, на который нужно выставить счет. Двойной клик левой кнопки мыши переносит номенклатуру в корзину в нижней части обработки в одноименной закладке.\n\n",
    "img": "/imgs/2_2.jpg"
  },
  {
    "id": 13,
    "name": "ЗАКАЗ КЛИЕНТА",
    "text": "Для того, чтобы появилось поле Договор, нужно перевыбрать Соглашение.\nЕсли используется соглашение, отличное от «ТИПОВОЕ СОГЛАШЕНИЕ Предоплата 100%», то в заказе необходимо указание договора, по которому осуществляется отгрузка и оплата. Если договор находится на согласовании и выбрать его сейчас невозможно, то в комментариях к заказу нужно указать номер и дату правильного договора. После согласования обязательно выбрать верный договор в заказе.\nЕсли с клиентом работаем по соглашению ТИПОВОЕ СОГЛАШЕНИЕ Предоплата 100%, то для бухгалтерии номер и дату реально заключенного договора/либо счета необходимо прописывать в комментариях к заказу.\nВ поле Комментарий прописываются условия по договору (оплата, доставка), а также вышеуказанная информация если она есть.\nЗакладка Товары заполняется номенклатура, которая будет списываться с остатков склада. В случае использования комплектов здесь указываются комплектующие. Если в отделе есть главные инженеры проектов, то данные о составах комплектов подают они. \n",
    "img": "/imgs/2_4.jpg"
  },
  {
    "id": 18,
    "name": "ЗАКАЗ КЛИЕНТА",
    "text": "В колонке Наименование указывается наименование комплекта согласно договору/спецификации/счету.\nВ колонке Цена – сумма цен по всем комплектующим. Общая сумма по комплекту (на закладке Товары на печать) должна быть равна сумме комплектующих (на закладке Товары). Закладка (наименование, количество, единица измерения, цена, НДС) должна быть заполнена обязательно в соответствии со спецификацией.\nВнимание!!! Обязательно прикладывать подписанную с обеих сторон спецификацию.",
    "img": "/imgs/2_9.jpg"
  },
  {
    "id": 21,
    "name": "ЗАКАЗ КЛИЕНТА",
    "text": "Документ можно распечатать (с предварительным просмотром и настройкой печати) или сохранить в файл. \nВ печатную форму счета на оплату подставляется тот банковский счет организации, который был выбран в Договоре, если договора нет, то подставляется основой банковский счет организации. \nВнимание!!! В печатную форму Счета на оплату подставляется текст комментариев, его нужно редактировать вручную, удаляя информацию для внутреннего использования (например, «раздельная поставка»)!!!\nВнимание!!! Если сотрудник официально не трудоустроен в Юридическом лице, от которого производит отгрузку, третью подпись с должностью и своим ФИО необходимо удалить из счета на оплату, если сотрудник числится в данном Юр. лице, проверяем наименование должности (поскольку наименование должности, которая выводится на печать автоматически, не совпадает с должностью, указанной в трудовом договоре с сотрудником)",
    "img": "/imgs/2_12.jpg"
  },
  {
    "id": 22,
    "name": "ДОГОВОР",
    "text": "Договор клиента можно создать в карточке Партнера по ссылке Договоры:",
    "img": "/imgs/3_1.jpg"
  },
  {
    "id": 23,
