### FPS VideoPlayer
* нашел метод у медиа плеера, который возвращает текущую позицию, можно вызывая раз  в каокето время, определять производительнось
* есть метод показывающий FPS рендеринга: http://stackoverflow.com/questions/5068349/how-can-i-get-rendered-frames-statistics-drawn-dropped-from-stagefright-media
* VideoView: можно отрисовку контроллить из VideoView http://developer.android.com/reference/android/view/SurfaceView.html#dispatchDraw(android.graphics.Canvas)
  View.draw, SurfaceView.dispatchDraw, android.graphics.drawable.Drawable.Callback.invalidateDrawable

### Custom player

* Есть идея подсчитывать количество ошибок проигрывания, если будут.
* Этот гад после того как в декодер кидают флаг что поток закончился, все равно дальше декодит.. @Measy
* И еще, на @Measy мквшный фильм сначала кидает кучу ошибок, и начинает проигрывать только к концу клипа
* Оказалось что на @Measy стандартный плеер не проигрывает из директории /data/data/com.nemobe....., а из карточки играет

