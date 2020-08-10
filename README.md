# tsetmc-dataset
tsetmc dataset - iranian stock

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
  
  ##### اطلاعات تماس
  * amirsh.nll@gmail.com
  * www.amirshnll.ir
