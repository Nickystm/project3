# UML-диаграммы.

### Описание системы доставки продуктов.
  Благодаря приложению доставки продуктов пользователь может заказывать еду через мобильное устройство в любое удобное место (если оно есть в радиусе доставки продуктов) и в любое время (в зависимости от времени работы ресторана). Пользователю на начальном этапе доступна регестрация: введение своего логина(почты/телефона), создание пароля, далее у него есть возможность просмотреть рестораны/магазины и их меню/каталог, после выбора понравившихся продуктов идёт оформление заказа, включающее в себя заполнение ещё одних данных пользователя, а именно - адрес, а также данные карт (при оплате заказа онлайн). Заказчик может отслеживать заказы, добавлять в избранное какие-либо позиции, а также отслеживать доставку. Рестораны/магазины несут за собой право менять меню, убирать или добавлять какие-либо позиции, менять описание блюд (то есть их составы), подтверждать заказы и искать курьеров для дальнейшей доставки, которые довезут заказ до пользователя, отслеживая их путь. Администратор управляет данными пользователя и ресторана, контолируют этапы производства заказов. Курьеры получают уведомления о новых заказах, и помимо самой доставки, по окончании работы меняют статус заказа с "в пути" на "завершённый". Приложение будет отправлять уведомеления пользователям, ресторанам и курьерам о статусе заказа. В конце концов система должна обеспечивать безопасное хранение данных, удобную навигацию, быструю обработку заказов и своевременную доставку.
  Для проектирования приложения было использованы 5 диаграмм.
1. Диаграмма вариантов использования. 
2. Диаграмма последовательности для процесса заказа еды через приложение.
3. Диаграмма состояний для заказа.
4. Диаграмма деятельности для описания процесса обработки заказа системой.
5. Диаграмму классов для системы.

Предоставлено несколько способов для открытия UML-диаграмм:
1) Открытие общего файла со всеми диаграммами через google drive.
* Открываем ссылку: https://drive.google.com/file/d/1gorup0ptbNLQx_9W_JoLYt8wQw3AxFCo/view?usp=sharing
* Нажать на эту кнопку:
  
  <img width="220" alt="Снимок экрана 2024-05-28 в 18 20 11" src="https://github.com/Nickystm/project3/assets/167700874/e4a58245-c3a0-426b-b023-945fb0e3ebd8">
2) Перейти по ссылкам.
* Диаграмма вариантов использования. https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1gorup0ptbNLQx_9W_JoLYt8wQw3AxFCo%26export%3Ddownload
* Диаграмма последовательности для процесса заказа еды через приложение. https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=CjHEgpYlPO23gQZJdxKg&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1gorup0ptbNLQx_9W_JoLYt8wQw3AxFCo%26export%3Ddownload
* Диаграмма состояний для заказа. https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=zGRalhDBLRNN9wPJ41dM&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1gorup0ptbNLQx_9W_JoLYt8wQw3AxFCo%26export%3Ddownload
* Диаграмма деятельности для описания процесса обработки заказа системой. https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=eoK-P6mQdpVGrM3S4e0f&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1gorup0ptbNLQx_9W_JoLYt8wQw3AxFCo%26export%3Ddownload
* Диаграмму классов для системы. https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=C5RBs43oDa-KdzZeNtuy&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1gorup0ptbNLQx_9W_JoLYt8wQw3AxFCo%26export%3Ddownload


