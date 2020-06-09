1. ExampleBitmaps - приложение отображает содержимое папки Images.
ExampleBitmapsViewModel.Next и ExampleBitmapsViewModel.Prev недоступны для пользователя, 
но должны быть доступны через Арм.
Также в Арм должен быть виден ExampleBitmapsViewModel.CurrentImg в виде строки.

2. ExampleButtons - просто показывает пользователю, какая кнопка была нажата последней.
В Арм необходимо отобразить всю историю нажатий (MainWindow.History) и
продублировать кнопки "1", "2" и "3".
Архитектура приложения намеренно плохая, не использующая MVVM.

