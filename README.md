
Сервис по доставке продуктов на дом. Сервис доступен как в приложении на ios, так и на android. Настроили фронтовую аналитику в AppMetrica, и в конце квартала проанализировать поведение пользователей, а также оценить эффективность каналов их привлечения. 

Имеются данные из AppMetrica за период с 1 января по 31 марта 2020, только по пользователям, зарегистрированным позднее 1 января 2020.

#### Описание данных 

date – дата совершения события\
event - событие\
app_install – установка приложения\
app_start – открыть приложения\
register – зарегистрироваться
search – перейти на страницу поиска товаров (каталог) \
open_item – открыть товар\
choose_item – отправить товар в корзину\
tap_basket – перейти в корзину\
purchase – подтверждение покупки\
gender – пол пользователя

os_name – платформа пользователя

city – город пользователя

device_id – идентификатор устройства пользователя

urm_source – канал, с которого пришел пользователь

yandex-direct – Яндекс директ\
google_ads – реклама в Google\
vk_ads – реклама в ВК\
instagram_ads – реклама в instagram\
facebook_ads – реклама в facebook\
referal – акция «приведи друга»\
Если стоит ‘-’, то канал не определен или это скачивание приложения напрямую или посещение не с рекламы 

purchase_sum – стоимость покупки (при совершении события ‘purchase’)

Обратим внимание на следующее:

- В выгрузке только уникальные действия пользователей за каждый день

- Можно миновать стадию установки приложения, если оно было установлено ранее

- Можно миновать стадию регистрации, если пользователь был уже залогинен на момент сессии. Однако незарегистрированные пользователи не могут оформить покупку. 
