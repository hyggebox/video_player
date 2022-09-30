# Браузерный видеоплеер

Минимальный браузерный видеоплеер, который может проигрывать/останавливать видео, убирать/включать звук и разворачивать видео на полный экран.

![video player](https://user-images.githubusercontent.com/80201470/193260347-3beda1f2-b911-44d2-9eb0-436fe55d922b.png)


## Запуск
Чтобы воспользоваться видеоплеером, нужно скачать все файлы из репозитория и запустить `index.html`

Проигрываемое видео подключается в файле `index.html` скриптом с помощью аргумента `src`:
```
  <script type="text/javascript">
    createPlayer({
      elementId: 'player',
      src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4',
    });
  </script>
```

## Демо-версия плеера
Демо-версия плеера доступна по [ссылке](https://hyggebox.github.io/video_player/).



## Цель проекта
Код написан в учебных целях.
