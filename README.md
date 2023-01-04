
# Weather App

Application to display the weather anywhere in the world🌍

#### [Video](https://www.linkedin.com/posts/mahmoudalaa2210_stateabrmanagement-api-requests-activity-6978941210748989440-Kffd?utm_source=share&utm_medium=member_desktop)

## Download App ![GitHub All Releases](https://img.shields.io/github/downloads/Thealphamerc/flutter_ecommerce_app/total?color=green)
<a href="https://github.com/MahmoudAlaa22/WeatherApp-Readme-file/releases/download/v1/weather.apk"><img src="https://playerzon.com/asset/download.png" width="200"></img></a>

![Logo](https://user-images.githubusercontent.com/60518534/210525117-464756de-6078-432e-99db-daf5aedb994a.png)


## Screenshots

  Splash Page                 |   Home Page        |  Drawer Page
:-------------------------:|:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/60518534/185890876-307fa5ac-ddda-4834-88f6-6cf31b09abd3.jpg)|![](https://user-images.githubusercontent.com/60518534/185890884-ef76daaa-3bfc-4352-9ce7-362210f57720.jpg)|![](https://user-images.githubusercontent.com/60518534/185890915-d2aa85be-4809-45a2-8016-3821af6d27bd.jpg)

## Weather States

  Rain                 |   Clouds        |  Thunderstorm
:-------------------------:|:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/60518534/185890699-1503cc36-f4e9-4d88-802c-8c2328f2181b.jpg)|![](https://user-images.githubusercontent.com/60518534/185890746-20c33dc4-4964-4e29-b83d-4b7e3b4858d9.jpg)|![](https://user-images.githubusercontent.com/60518534/185890779-c37ef86d-755c-4995-896b-f7093db441e9.jpg)

  Snow                 |   Snower Rain        |  Mist
:-------------------------:|:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/60518534/185890789-0b56c57c-16a7-48a0-9ebf-bc8dc4f26aaa.jpg)|![](https://user-images.githubusercontent.com/60518534/185890821-6a93164e-1f21-46e3-9399-633d9046a295.jpg)|![](https://user-images.githubusercontent.com/60518534/185890855-e053a2f6-bf8c-4c53-a647-e9dedb1e63c9.jpg)

## Features

- Beautiful UI.
- Know the temperature of your location.
- Know the percentage of clouds, humidity, and wind.
- you can search for any city name you want to know its temperature.

## API Reference

#### [OpenWeather site](https://openweathermap.org/api)

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

After getting the key go to

```
lib -> common -> api -> api.dart
```

And add your key when you find this sentence👇

```
ADD YOUR API KEY HER
```

Then add this line in your termenal

```
flutter pub run build_runner build
```

## Directory Structure

```
lib
│────common
│    │── api
│    │    │── api_controller.dart
│    │    │── api_controller.g.dart
│    │    └── api.dart
│    │── app_routes
│    │    └── getx_routes.dart
│    │── assets
│    │    └── images.dart
│    │── const
│    │    │── color_manager.dart
│    │    │── font_manager.dart
│    │    │── text_const.dart
│    │    └── text_style_manager.dart
│    │── controller
│    │    └── app_bindings.dart
│    └── theme
│         └── theme.dart
│───model
│    │── country_model.dart
│    │── country_model.g.dart
│    │── weather_model.dart
│    └── weather_model.g.dart
│───modules
│    │── home_page
│    │    └── state_management
│    │    │    └── home_page_controller_getx.dart
│    │    │── widgets
│    │    │    │── temperature.dart
│    │    │    │── weather_info.dart
│    │    │    └── weather_page.dart
│    │    │── data_service.dart
│    │    └── home_page.dart
│    │── search_by_city_page
│    │    └── state_management
│    │    │    └── search_by_city_getx.dart
│    │    └── widgets
│    │    │    └── city_widget.dart
│    │    └── search_by_city_page.dart
│    └── splash
│         └── state_management
│         │    └── splash_controller_getx.dart
│         └── widgets
│         │    └── splash_widget.dart
│         └── splash.dart
│───widgets
│    │── animated_button_widget
│    │    └── animated_button_widget.dart
│    │── blur_widget.dart
│    └── drawer_page.dart
└───main.dart    
```

## Pull Requests

I welcome and encourage all pull requests. It usually will take me within 24-48 hours to respond to any issue or request.

## 🛠 Skills

Flutter, Dart, Lottie, Audio, Geolocator.

## Packages

```
  cupertino_icons: ^1.0.2
  get: ^4.6.5
  google_fonts: ^3.0.1
  dio: ^4.0.6
  retrofit: ^3.0.1+1
  retrofit_generator: ^4.0.3
  build_runner: ^2.2.0
  json_annotation: ^4.6.0
  json_serializable: ^6.3.1
  flutter_svg: ^1.1.1+1
  lottie: ^1.4.1
  geolocator: ^7.1.0
  flutter_overlay_loader: ^2.0.0
  flutter_offline: ^2.1.0
  just_audio: ^0.9.28
  blur: ^3.1.0
  flutter_zoom_drawer: ^3.0.3
  country_state_city_picker: ^1.2.8
```

## Feedback

If you have any feedback, please reach out to us at mahmoud3laa2210@gmail.com

## 🔗 Links

[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MahmoudAlaa22)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoudalaa2210/)
