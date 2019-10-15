# Требования к проекту

### Содержание

1.[Введение](#1)

2.[Требования пользователя](#2) <br>
  
 2.1 [Программные интерфейсы](#2.1) <br>
  
 2.2 [Интерфейс пользователя](#2.2) <br>

 2.3 [Характеристики пользователей](#2.3) <br>

3 [Системные требования](#3) <br>
 
 3.1 [Функциональные требования](#3.1) <br>
  
 3.2 [Нефункциональные требования](#3.2) <br>
    3.2.1 [Атрибуты качества](#3.2.1) <br>
       3.2.1.1 [Требования к удобству использования](#3.2.1.1) <br>
       3.2.1.2 [Требования к безопасности](#3.2.1.2) <br>
 	3.2.2 [Ограничения](#3.2.2) <br>
 
 4 [Обзор аналогов](#4) <br> 
  
### Глоссарий
* Продукт (или товар) - кондитерское изделие, используемое для продажи.
* Корзина - набор продуктов, которые выбрал для предварительной попуки пользователь, можно изменять.
* Безопасность - требования к проекту по защите пользовательский данных в процессе его функционирования.


### 1. Введение <a name="1"></a>

В мире современных технологий все большую популярность приобретают веб-приложения, которые позволяют пользоваться 
различными сервисами прямо из браузера, однако не все из них предоставляют полноценный функционал и удобный интерфейс 
пользователя. Задачей проекта является реализовать полноценное, удобное для работы пользователя приложение для работы с 
кондитерским магазином. 

### 2. Требования пользователя <a name="2"></a>


#### 2.1. Программные интерфейсы <a name="2.1"></a>


Проект будет реализован на языке программирования Java 1.8. Используются также Spring Framework и Angular Framework.
Для хранения данных будет использоваться MySQL.


#### 2.2. Интерфейс пользователя <a name="2.2"></a>

- Главная страница<br> 
![Home page](https://raw.githubusercontent.com/RSlabodchikov/CandyShop/master/images/mockups/Home.png) 
- Страница товара<br> 
![Product page](https://raw.githubusercontent.com/RSlabodchikov/CandyShop/master/images/mockups/Product.png)
- Аккаунт пользователя<br> 
![User account](https://raw.githubusercontent.com/RSlabodchikov/CandyShop/master/images/mockups/Account.png)
- Каталог продуктов<br> 
![Shop](https://raw.githubusercontent.com/RSlabodchikov/CandyShop/master/images/mockups/Shop.png)
- Карзина<br> 
![Cart](https://raw.githubusercontent.com/RSlabodchikov/CandyShop/master/images/mockups/Cart.png)

### 2.3. Характеристики пользователя <a name="2.3"></a>

Любой пользователь с доступом в интернет, который хочет приобрести кондитерское изделие.

### 3. Системные требования <a name="3"></a>


#### 3.1. Функциональные требования <a name="3.1"></a>


1. Возможность зарегестрировать и изменять свой аккаунт.
2. Предоставление актуальной информации об товаре.
3. Возможность детально рассмотреть товар и выбрать способ оплаты.
4. Предоставить пользователю возможность выбрать несколько товаров в один заказ.
5. Предоставить пользователю возможность сохранить заказ в корзину и завершить его позже.
6. Предоставить пользователю возможность восстановить свою корзину. 
 

### 3.2 Нефункциональные требования <a name="3.2"></a>

#### 3.2.1 Атрибуты качества <a name="3.2.1"></a>
Важными атрибутами приложения являются: относительно малые требования для пользователя и высокая производительность,
 а именно отсутствие задержек при навигации в приложении и прогрузке ее страниц. Также атрибутами качества являются:
  легкость использования из-за отсутсвия лишнего функционала, отсутствие рекламы, защищенность пользовательских данных.
##### 3.2.1.1 Требования к удобству использования <a name="3.2.1.1"></a>
1. Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента.
2. Элементы товаров содержат ссылки на соответствующие товары.
3. Для более удобного просмотра продуктов реализовать пагинацию.
##### 3.2.1.2 Требования к безопасности <a name="3.2.1.2"></a>
1. Никто, кроме пользователя и администратора не имеет доступа к личным данным.
2. При регистрации и последующем использовании данные пользователя кодируются.
#### 3.2.2 Ограничения <a name="3.2.2"></a>
* Приложение реализовано на языке Java.
* Приложение доступно для браузера GoogleChrome версии не ниже 3.29, для остальных браузеров ограничений нет.

### 4. Обзор аналогов <a name="4"></a>

Одними из аналогов данного приложения являются https://bakenart.by и https://pastila.by.
Главными отличиями являются масштаб и используемые технологии.