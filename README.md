# MVVM Architecture Android Sample Shoe Management System

## About Project
This Project, developed using MVVM architecture, connects to a RESTful API with Retrofit, is an Android application that allows users to manage their shoe data. Users can perform basic CRUD Operations.

## Libraries and Technologies Used

- **[OkHttp](https://square.github.io/okhttp/) and [Retrofit](https://square.github.io/retrofit/):** Used to send HTTP requests and connect to the API.
- **Gson:** Used for processing JSON data.
- **[Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines):** Used for asynchronous programming.
- **AndroidX Components:** RecyclerView, AppCompat, Material Design components and other AndroidX libraries were used.

## Features
**Basic CRUD Operations:**
- **Add Shoes:** Users can add new shoe information.
- **Update Shoes:** Users can update existing shoe information.
- **Delete Shoes:** Users can delete existing shoes.
- **View Shoes:** Users can view existing shoes.


## MVVM Architecture

![mvvm-diagram](https://github.com/meoty/xdxd/assets/141409558/7bf4c1d8-ba8a-4f69-8833-f3650c67404d)

This project was developed using the MVVM (Model-View-ViewModel) architecture. The role of each component is as follows:

- **Model:** Shoe data model classes were used to represent the data returned from API calls.
- **View:** User interface components
- **ViewModel:** Middleware classes that manage the connection to the UI and execute the business logic.

## The app has following packages:

![image](https://github.com/meoty/xdxd/assets/141409558/6d7dc035-b003-49f3-9b80-391875f6d8f2)


## How to Launch

1. Clone this repository: `git clone https://github.com/kullanici_adi/AyakkabiMagazasi.git`
2. A database with JSON Output like this
   ```
   "Shoes": {
    "ShoeBrand": "",
    "ShoeColour": "",
    "ShoeId": "",
    "ShoeModel": "",
    "ShoePrice": "",
    "ShoeSize": ""
   }
   ```
4. Open the project folder in Android Studio.
5. Run the application using an Android device or emulator.

## References

- ViewModel https://developer.android.com/topic/libraries/architecture/viewmodel
- LiveData https://developer.android.com/topic/libraries/architecture/livedata
- Android Architecture Blueprints https://github.com/googlesamples/android-architecture
- Android Jetpack: ViewModel https://www.youtube.com/watch?v=5qlIPTDE274

## Contributions

If you would like to contribute to this project, please submit a pull request. We welcome your contribution!
