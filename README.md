<h1 align=center>Django Drinks API 🥤</h1>
<p align=center>
  Drinks <strong>CRUD</strong> API made with ❤️ & <a href="https://www.djangoproject.com/">Django</a>
</p>

---

## Usage

### How is this API organized?

This API will give you the data about some drinks in json format.  
Each object of the drinks will have `id` & `name` & `description` made in this format:  
```json
[
  {
    "id": 1,
    "name": "Some juice",
    "description": "Very yummy juice 😋"
  },
  {
    "id": 2,
    "name": "Another juice",
    "description": "Also great juice made from ...."
  }
]
```

_This API is runing mainly on `domain.com/drinks/`_

---

### Example

```json
[
  {
    "id": 1, 
    "name": "Apple juice", 
    "description": "so sweet"
  }, 
  {
    "id": 2, 
    "name": "Orange juice", 
    "description": "awesome"
  }
]
```

---

## Contribution 

### Setup 

If you want to contribute to this project all you'll need is first of all a virtual enviroment to run your debuging version on it.  
We suggest either using [python3.10-venv](https://docs.python.org/3/tutorial/venv.html) or [virtualenv](https://virtualenv.pypa.io/).  

For setting up Django and rest_framework
```bash
pip3 install django-admin
pip3 install djangorestframework
```

That'll be all what you need as setup, the you can run the debugging server with this command:  
```bash
python3 manage.py runserver
```

---

### Pull Requesting

There's some recommendations to get your pull request aproved:  

1. Keep your commits clean and self-explained
2. Explain what exactly will your pull request add to the application
3. Add related features
4. Don't make changes to things that doesn't relate to your pull request topic
5. Allow maintaners to edit

If you follow these rules then your pull request will be reviewed & maybe added 😄

---

<h6 align=center><a href="./LICENSE">MIT Licanse | Sadullah-TANRIKULU</a></h6>
