# EasyFood 🍲📱

## Overview

Welcome to EasyFood! This app is designed to make the process of cooking easier by providing detailed information about selected meals, including step-by-step instructions through instructional videos.

## Features

- **Meal Selection 🍽️:**
  - Browse and choose from a variety of meals to prepare.

- **Detailed Information 📋:**
  - Get comprehensive information about each selected meal, including ingredients and nutritional details.

- **Video Instructions 🎥:**
  - Access step-by-step cooking instructions through instructional videos for a more visual cooking experience.

- **Favorites and History ❤️🕰️:**
  - Mark favorite meals for quick access and view cooking history.


# Preview
![1](https://user-images.githubusercontent.com/78867217/143778911-20c19914-7f67-41c9-ab0f-0a609f9f07e7.jpg)

![2](https://user-images.githubusercontent.com/78867217/143778942-5ec4c4fc-2e02-4acc-86f8-7bd69c4837b1.jpg)

![6 (1)](https://user-images.githubusercontent.com/78867217/143781457-104ca064-80ad-4cb9-82f1-b2e8b6abf3b2.jpg)

![3](https://user-images.githubusercontent.com/78867217/143778946-0ed6e7bd-8d00-46d0-9aac-9b2926d44194.jpg)

![4](https://user-images.githubusercontent.com/78867217/143778948-6b290e99-0212-4116-b3c2-08388852146f.jpg)

![5](https://user-images.githubusercontent.com/78867217/143778949-deda1f32-feda-4dcc-b45c-c287271c7a70.jpg)


# Libraries and technologies used
- Navigation component : one activity contains multiple fragments instead of creating multiple activites.
- Retrofit : making HTTP connection with the rest API and convert meal json file to Kotlin/Java object.
- Room : Save meals in local database.
- MVVM & LiveData : Saperate logic code from views and save the state in case the screen configuration changes.
- Coroutines : do some code in the background.
- view binding : instead of inflating views manually view binding will take care of that.
- Glide : Catch images and load them in imageView.




