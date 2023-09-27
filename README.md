# Model-View-ViewModel
MVVM има три компонента: Model, View и ViewModel.
Всеки един от тях има специално предназначение

![Pattern](https://raw.githubusercontent.com/CDevv/mvvm-explanation/main/diagram.png?token=GHSAT0AAAAAACH5XDK7YQG6OWZ343CY2E6WZIT2MTA)

## View
View-то е това, което потребителят вижда на екрана.
Описва структурата на потребителския интерфейс. Също отговаря и за взаимодействия с потребителя като натискане с мишка

## Model
Тук се съдържат данните за приложението и може да се използва като слоя за база данни

## ViewModel
Имплементира команди и функции, чрез които да се променя изгледа (View). ViewModel-а няма референция към View, а само съобщава за промени.

В MVVM се използва език, наречен XAML. Използва се, за да се синхронизират данните между View и ViewModel.