# Share
ПРОЕКТ Share

Краткое описание Сервис (веб-приложение) доступный через браузер, с возможностью зарегистрироваться как пользователь, разместить свою технику (велосипед, самокат) для возможной краткосрочной аренды и выбрать технику для аренды. Сервис бесплатный для владельцев арендуемых транспортных средств с оплатой владельцу транспортного средства по фиксированному тарифу.

Роли пользователей:

администратор сервиса (проверка и удаление аккаунтов, установка и подтверждение договорной стоимости залога, прием оплаты аренды и передача оплаты собственнику, прием и возврат залога, обработка отзывов)
пользователь аренды или арендатор (возможно совмещение) (добавление транспортного средства, периода, в который транспортное средство свободно для аренды и ограничения на использование, добавление отзыва об аренде, данных о залоге, если используется залог, оформление заявки аренды, оформление заказа на аренду, оплата, оставление залога)
незарегистрированный пользователь (просмотр главной страницы и контактов, общая информация о сервисе и размещенные отзывы)
Страницы:

главная страница (общая информация, контакты, авторизация, размещенные администратором отзывы, галерея фото)
личный кабинет пользователя (возможность добавить свой транспорт, перейти к подбору транспорта для аренды, оставить заявку, подтвердить заявку на свой транспорт, сдать в аренду, подтвердить прием оплаты и возврат транспортного средства, подтвердить прием залога в случае отсутствия возврата транспорта, отображение подтвержденных заявок и возможность сделать заказ, просматривать историю заказов и статус текущего заказа)
каталог подбора аренды (фильтр по типу средства и времени аренды, возможность отправить заявки)
карточка транспорта (фото, модель, тип средства, свободное время для аренды, стоимость аренды и залога, возможно отзывы о владельце или средстве)
карточка заказа по кнопке «создать заказ» из подтвержденной заявки. Отображение транспортного средства, данных владельца, данных арендатора, условий аренды, текущего статуса, возможности менять статус
панель администрирования (таблица каталога с возможностями вносить коррективы, модерация пользователей, модерация отзывов, таблица заказов с возможностью вносить изменения по факту внесения и выдачи залога, выдачи и возвращения транспорта, оплаты и передачи оплаты владельцу)
История заказа: Из каталога можно сделать заявку на определенный транспорт на определенное время от определенного пользователя (только зарегистрированные) Заявки отображаются в таблице текущих заявок у пользователя и у владельца транспортного средства Только владелец может подтвердить или отклонить заявку, если она не подтверждается в срок до начала аренды, она автоматически отклоняется. При подтверждении заявки, в таблице появляется опция создать заказ — только у пользователя, который хочет взять средство в аренду. Если он этого не делает, заявка автоматически отклоняется с начала даты аренды или через три часа после подтверждения, в случае, если на это транспортное средство есть еще заявки. Кто заявил первый — тот имеет приоритет. При создании заказ приобретает статус «новый», и пользователь может внести залог, а также (по желанию?) предоплату. Заказ приобретает соответствующий статус «внесен залог» Связь между пользователями (это не минимум, но можно добавить потом) — возможность отправлять сообщения от арендатора к владельцу и обратно. После передачи залога производится передача в аренду транспортного средства, владелец отмечает этот факт в заказе, меняя статус. После возврата транспортного средства он же меняет статус (и ему перечисляются деньги). После получения денег и подтверждения статус заказа меняется администратором на «оплачен», пользователю возвращается залог. После подтверждения возвращения залога, заказ получает статус «завершен». До момента перечисления оплаты в случае отмены пользователем или в случае не получения на руки транспортного средства и возвращения залога и оплаты обратно арендатору, заказ получает статус «отменен».

Дополнительные функции, которые могут быть, а могут пока нет:

оплата и залог (можно сначала сделать бесплатный вариант)
чат между участниками сделки (можно сначала обойтись выдачей контактов)
подробный отбор при поиске (можно добавить позже, по умолчанию выводить в поиск только то, что имеет доступное время, оставить заявку можно только на выбор из доступного времени для каждого транспортного средства)
галерея фото на главной странице и отзывы
управление личным кабинетом (смена пароля, личной информации) — можно добавить потом