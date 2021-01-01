# tsetmc-dataset
tsetmc dataset - iranian stock

* Author: Amir Shokri
* Author Email: amirsh.nll@gmail.com
* Last Update: 1 january, 2021
* Data format: JSON, SQL Data
* Contribute: Fork and Push Requests :)

## جزئیات دیتاست

* tsetmc_stock_category
  * ID : فیلد auto increment
  * category_id : کد گروه در سیستم tsetmc
  * category_title : عنوان دسته بندی گروه
  * category_tsetmc_id : کد صفحه ی دسته در سیستم tsetmc
* tsetmc_stock_company
  * ID : فیلد auto increment
  * name : عنوان شرکت سهام (نام شرکت، نام سهم)
  * tsetmc_code : کد صفحه ی سهم در سیستم tsetmc
  * group_code : کد گروه در سیستم tsetmc (همان category_id در جدول قبلی می باشد.)
  
  ### مرجع داده
  **داده ی فعلی از سایت [بورس](http://www.tsetmc.com/) جمع آوری شده است**
  
  #### کپی رایت
  **این داده توسط بنده به صورت دستی جمع آوری شده و تنها برای استفاده ی غیرتجاری کاربرد دارد در صورت علاقه برای استفاده تجاری با من تماس بگیرید**


<br />
<br />

### Other datasets collected by me
* [Persian-Swear-Words](https://github.com/amirshnll/Persian-Swear-Words/)
* [persian-stop-word](https://github.com/amirshnll/persian-stop-word/)
* [persian-sms-spam-word](https://github.com/amirshnll/persian-sms-spam-word/)
* [tsetmc-dataset](https://github.com/amirshnll/tsetmc-dataset/)
* [persianwordjson](https://github.com/amirshnll/persianwordjson/)
* [English-Persian-Word-Database](https://github.com/amirshnll/English-Persian-Word-Database/)
* [Covid-patient-datasets](https://github.com/amirshnll/Covid-patient-datasets/)
