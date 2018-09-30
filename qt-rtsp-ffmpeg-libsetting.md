# ffmpeg 库的设置，最好还是使用pkgconfig
LIBS += `pkg-config --libs libavcodec libavutil libavdevice libavformat libavfilter libpostproc libswresample libswscale`
直接写-l*容易漏掉依赖库。

