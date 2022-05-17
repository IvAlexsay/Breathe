# Классы приложения

Данное приложение написано для Android на языке Kotlin. Оно содержит 5 классов: MainActivity, StartScreen, TimeSettings, BreathExercise и TimeData.

Класс MainActivity является системным классом, с которого начинается запуск приложения. Его единственная задача состоит в том, что он перенаправляет пользователя на стартовый экран.

Класс StartScreen служит основным экраном приложения, который содержит кнопку перехода в настройки и кнопку запуска, а так же отображает текущие настройки дыхательного упражнения. Так же в этом классе происходит считывание настроек из файла.

Класс TimeSettings обрабатывает изменения в настройках приложения, а именно: выключение и выключение звука и вибрации, изменения параметров упражнения (время вдоха, задержки дыхания, выдоха и количества циклов). Так же в этом классе производится запись измененных настроек в файл.

Класс BreathExercise запускает таймер дыхательного упражнения с текущими настройками, а так же воспроизводит звук и вибрацию по завершению каждой части упражнения.

Класс TimeData хранит все настройки приложения, а именно: время вдоха, задержки дыхания и выдоха, количество циклов, включен ли звук и вибрация.

