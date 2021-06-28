#  Random Facts API 👋🧑👩

+ An API that will return Random Facts API 🕵️🕵️‍♀️👨‍🔬
+ + Dedicated To All Facts Lovers ❤️

## Usage:

+ `https://random-facts-api.herokuapp.com` to get the documentation.
+ `https://random-facts-api.herokuapp.com/api/Random-Facts/all` to get all the Random Facts at once.
+ Change `all` to parameter `?number=` to specify the number of Random Facts you want to receive.
+ Change `all` to parameter `?index=` to specify the index of the Random Facts you are targeting.

This project is hosted by [Heroku](https://www.heroku.com/)

## Rebuild the project:
+ Clone the repo.
+ Run `python -m venv .env` to create a virtual environment.
+ Run `source .env/bin/activate` to activate the virtual environment.
+ Run `pip install requirements.txt`.
+ Run `python app.py`.
+ App starts at `http://localhost:5000` by default, but can be configured with a `.env` file. 

## Example:

+ `https://randon-facts-api.herokuapp.com/api/Random-Facts?number=1` returns: ↓
```JSON
[
  {
    "Place_Name": "Jangoos"
  }
]
```

+ `https://randon-facts-api.herokuapp.com/api/Random-Facts?number=2` returns: ↓
```JSON
[
  {
    "Place_Name": "Ahammed"
  }, 
  {
    "Place_Name": "Joel"
  }
]
```
