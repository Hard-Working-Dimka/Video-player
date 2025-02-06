# Видео плеер
Используется для удобного просмотра видео.
![image](https://github.com/user-attachments/assets/9a25ea86-a479-4c17-a4e0-cbac711df713)


## Функциональность 
Плеер имеет панель управления, которая содержит следующие элементы:
* Кнопка паузы/воспроизведения видео
* Кнопка включения/выключения звука видео
* Кнопка открытия видео на весь экран

## Выбор видео
Взято из [документации](https://github.com/devmanorg/video-player-jslib/blob/master/README.md) библиотекиб используемой для создания данного плеера.

По умолчанию плеер воспроизводит видео по [этой ссылке](https://dvmn.org/media/filer_public/78/db/78db3456-3fd3-4504-9ed9-d2d1fd843c0b/highest_peak.mp4). 

Если хочется выбрать другое видео, с помощью аргумента `src` плееру можно указать какое видео проигрывать, ссылки обязаны заканчиваться расширением файла:
```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```

## Пример работы
Рабочий плеер можно открыть по [ссылке](https://hard-working-dimka.github.io/Video-player/).
