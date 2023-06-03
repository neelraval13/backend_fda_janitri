# Food Delivery Application - Backend(Django)

We have created an API with Django & REST framework which will manage, save and store all the data React will send us.

[React Frontend](https://github.com/neelraval13/frontend_fda_janitri)
## Deployment

To deploy this project, you'll have to follow a few steps

#### 1. Download the reuquirements of the project

```bash
  pip install -r requirements.txt
```

#### 2. Run the following commands

a. Activate your virtual environment 

```bash
  source venv/bin/activate
```
 - [How to install and activate python virtual environment](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)

b. Do the migrations, createsuperuser and runserver.

```bash
  python manage.py migrate
```

```bash
  python manage.py createsuperuser
```

```bash
  python manage.py runserver
```

#### You shall find the project on your localhost, where you can  visit the following urls 

1. admin/
2. api/
3. api/table-list/ [name='table_list']
4. api/table-detail/<int:pk>/ [name='table_detail']
5. api/order-list/ [name='order_list']
6. api/order-detail/<int:pk>/ [name='order_detail']
7. api/order-item-list [name='order_item_list']
8. api/order-item-detail/<int:pk>/ [name='order_item_detail']
9. api/product-list/ [name='product_list']
10. api/product-detail/<int:pk>/ [name='product_detail']
11. api/category-list [name='category_list']

