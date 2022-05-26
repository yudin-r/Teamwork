# Teamwork
Teamwork - приложение для управления проектами. Каждый пользователь может стать как участником, так и создателем проекта. Основным инструментом взаимодействия, является облачное хранилище от Google - Firebase, из-за этого приложение требует наличие интернет соединения.
## 🚀 Основные функции
- В приложении присутствует EventListener(ы) (слушатель изменений) для обновления списка заданий и проектов в реальном времени.
> Сортировка выполняется не при получении готового списка, а **при запросе, через orderBy.**
- Удаление элементов списка происходит свайпом влево, такая функция реализована с помощью ItemTouchHelper и библиотекой [RecyclerViewSwipeDecorator](https://github.com/xabaras/RecyclerViewSwipeDecorator.git)
- В основном поля имеют textWathcer, поэтому придётся вводить обязательные данные :upside_down_face:
- Из-за зависимости приложения от интернета при запуске проверяется интернет соединение
## ℹ️ Иная информация
- Приложение поддерживается :man_technologist:
- Последняя версия: 1.6 (25.05.22)
- Не исключено наличие каких-то микро-сбоев или проблем, все-таки не все возможно оперативно одному поймать, но **работы над сведением проблем к минимуму идут**
