# workout_tracker

This is a a CLI workout tracker app. Track your daily workout via a natural language processing API. Just type what you done today, and API will take care of the rest, your input will be added to your google sheets file.

## How does it work ?

1. Get your APP_ID and API_KEY from Nutritionix and add it to ".env" file,
>https://developer.nutritionix.com/

2. Sign up to Sheety and connect it to your google sheets account, create a new project, get your project SHEET_ENDPOINT, set the authenticaton methot to Bearer and assign a self generated TOKEN, and add it to ".env" file,
> https://sheety.co/

3.  Add your profile info to ".env" file,
4.  Run the code
