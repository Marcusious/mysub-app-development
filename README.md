# mysub Mobile App Source Code

This is the official source code for the **mysub** mobile application. Coded with Flutter.

## Developers

Please read the [docs/](docs/) (Outdated) files, as it contains the requirements for building and running the app, and information about guidelines to follow when working on it.

# Project Structure (Outdated)

```
mysub/
├──── /assets                       # Assets of the app
|        ...
├──── /lib/
|        ...
├──────── enums/                    # Enum files
|   └────────── view_state.dart     # Defines view states i.e Idle, Busy, Error
|        ...
├── model/                          # Data models
|   └───────── my_sub.dart          # MySub User data model
|        ...
├── services/                       # Backend Services
|   └── firebase_service.dart       # handles firebase auth and database calls.
|        ...
├── ui/                             # UI layer
|  ├── view/                        # Views
|  |  └───── view.dart              # Defines the Abstract view
|  |  └───── home_view.dart         # Defines Home View
|  |  └───── login_view.dart        # Defines Login View
|   |    ...
|  ├── viewmodel/                   # View Model Layer
|  |
|  └── widget/                      # Shared Widgets
|
├── utils/                          # utilities such as api_utils, app_exceptions.
├── config.dart                     # Configuration file
├── router.dart                     # Routes of the App.
├── firebase_options.dart           # dependency injection using get_it
├── mysub.dart                      # <3 of the app
```
