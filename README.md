![Showcase](./Banner_eShop.png)

# Flutter eCommerce UI Kit with Clean Architecture

This Figma template provides a clean and modern design for building eCommerce applications. Designed specifically with light mode, it focuses on clarity, usability, and aesthetics to meet the needs of both designers and developers.

## Contact for Purchase

If you're interested in purchasing this product or need more information, please contact us:

- **Email:** [phankiet.it@gmail.com](mailto:phankiet.it@gmail.com)
- **Telegram:** [https://t.me/phankiet](https://t.me/phankiet)
- **Learn more about our services:** [https://vietconsultant.asia](https://vietconsultant.asia/)

## Showcase

![Showcase](./Showcase_eShop.png)

## Key Features

- **Complete E-commerce UI Flow**: Includes essential screens like onboarding, authentication, home, product listing, product details, wishlist, shopping cart, checkout, profile, and order tracking
- **Reusable Components**: Pre-designed elements like buttons, navigation bars, product cards, and input forms
- **Scalable Design System**: Organized typography, color styles, and spacing
- **Light Mode Design**: Optimized for clarity and readability
- **Responsive Layouts**: Adapts to various screen sizes
- **Organized Layers**: Well-structured and properly named

## Target Audience

- Designers needing ready-made UI kit for prototyping
- Developers looking for clean design implementation
- Businesses wanting professional eCommerce platforms

## Package Contents

- 20+ professionally designed screens
- Fully layered Figma file
- Reusable design components
- Light mode optimized design

## Project Structure

```bash
├── lib
│   ├── main.dart
│   ├── core
│   │   ├── failure.dart
│   │   ├── request.dart
│   │   ├── service_locator.dart
│   │   ├── theme.dart
│   │   ├── validator.dart
│   ├── extensions
│   │   ├── number_extension.dart
│   │   ├── string_extension.dart
│   ├── data
│   │   ├── datasource
|   |   |   ├── api_constants.dart
│   │   ├── ├──authen_remote_datasource.dart
│   │   ├── models
│   │   │   ├── authen
│   │   │   │   ├── user_model.dart
│   ├── domain
│   │   ├── entities
│   │   │   ├── authen
│   │   │   │   ├── user.dart
│   │   ├── usecases
│   │   │   ├── authen_usecase.dart
│   ├── presentation
│   │   ├── blocs
│   │   │   ├── authen
│   │   │   │   ├── authen_bloc.dart
│   │   │   │   ├── authen_event.dart
│   │   │   │   ├── authen_state.dart
│   │   ├── pages
│   │   │   ├── authen
│   │   │   │   ├── authen_page.dart
│   │   │   ├── widgets
│   │   │   │   ├── base_cached_image.dart
│   ├── routes
│   │   ├── app_router.dart
│   │   ├── app_routes.dart
│   ├── services
│   │   ├── dialog_service.dart
│   │   ├── toast_service.dart
│   │   ├── user_cache_service.dart
│   ├── widgets
│   │   ├── input
│   │   │   ├── date_time_form_field.dart
│   │   ├── listview
│   │   │   ├── base_listview_separated.dart
│   ├── utils
│   │   ├── device_utils.dart
pubspec.yaml
analysis_options.yaml
```
