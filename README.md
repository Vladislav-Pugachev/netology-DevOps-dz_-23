### 1.
> Документоориентированные базы данных, лучше всего подходит для хранения не связанных между собой документов

> Реляционные базы данных, данные будут сруктурированы по таблицам (склад, дорога) 

> Иерархические базы данных, для хранение данных используется родительско-дочернюю модель

> Ключ-значение, может хранить большой объем данных и хорошо подходит для временного хранеия ключей

> Реляционные базы данных, структурированные данные по столбца (магазин, товар, покупатель)

### 2.

> AС; PA/EL

> AP; PA/EC

> PС; PC/EC 

### 3.

> Я думаю что сочетание в одной системе принципов BASE и ACID невозможно, так как принципы пострение систем на том или ином принципе слишком различны, и если BASE в основном применяются в NoSQL, то ACID это про SQL

### 4. 

> Pub/Sub это система обмена сообщениями между авторами сообщении и подписчиками, есть два варианта доставки сообщении pool и push. Основным недостатком данной системы является сложность настройки для малых систем, при большом потоке сообщении увеличиваются задержки доставки, возможно доставка сообщении не по адресу
