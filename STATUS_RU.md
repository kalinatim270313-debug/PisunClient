# Статус PisunClient 0.7.0

Подготовлены Java Activity, меню, JNI bridge и экспериментальный C++ hook AutoSprint для ARMv7 Minecraft PE 1.1.5.

Проверенные имена символов в исследованной библиотеке:
`_ZN16MoveInputHandler4tickER11LocalPlayer`
`_ZNK16MoveInputHandler15isMovingForwardEv`
`_ZN11LocalPlayer12setSprintingEb`

## Ограничения
- APK не собран и не запускался на устройстве.
- C++ hook не прошёл сборку Android NDK и runtime-проверку.
- Загрузка Substrate и разрешение символов требуют проверки на целевом устройстве.
- Minecraft/Variable DEX и сторонние native-библиотеки не включены в репозиторий.

AutoSprint нельзя считать подтверждённо рабочей функцией до тестирования.
