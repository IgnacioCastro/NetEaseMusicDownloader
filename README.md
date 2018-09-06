# NetEaseMusicDownloader

[中文说明](https://github.com/Kito0615/NetEaseMusicDownloader/blob/master/README_CN.md) 

![](https://img.shields.io/badge/Platform-Python3-009eff.svg) ![](https://img.shields.io/badge/Windows-Supported-00efff.svg)  ![](https://img.shields.io/badge/MacOS-Supported-00efff.svg) ![](https://img.shields.io/badge/Linux-Supported-00efff.svg) ![](https://img.shields.io/badge/WebAPI-Failed-ee0000.svg)

> **NOTE:** In this script, I used some api via [AD's API](https://api.imjad.cn/). Thanks. This 
> script is for personal use only. It cannot be used for any commercial 
> activities. All legal issues are not related to the author.
>
> **NOTE**: With new source from [QQMusic](http://y.qq.com) added, the source API is get from ite [webpage](http://y.qq.com), **all right revserved by [QQMusic](http://y.qq.com)**. This was **only for study**.

#### Update:2018-09-06

1. **New version of Downloader.**Add some options for the script.

2. Usage : `python3 NetEaseMusicDownloader.py ` `[OPTIONS]` `URL` or `NetEaseMusicDownloader`  `[OPTIONS]` `URL`

3.  Option List:

   ​	-h, —help 			: show help message.

   ​	-s, —single			: specific the url is a single music.

   ​	-l, —list				: specific the url is a list.

   ​	-v, —video			: specific the url is a music video.

   ​	-r, —range RANGE	: specific to download music in range.

   ​						  RANGE format like '1,2, 5-7,18'

   ​	-a, —auto 			: add to iTunes Library automatically.

   ​	-f, —folder FOLDER	: specific the destination folder.

#### Update:2018-08-09

1. Add Lame Tag for iTunes.
2. Now offcial web api failed, still using thrid-part API from AD. I will fix this ASAP.

#### Update: 2018-07-17

1. Add API from official website crack.
2. Add song best bit rate detect.

#### Update: 2018-06-14

1. Add ask for "Add to iTunes automatically".
2. Fixed break down when file exists or search in QQMusic failed.

#### Update:2018-05-28

1. Use new non-offcial api which get from the web replaced the old api.

#### Update:2018-05-22:

1. Now you can use this tool to download songs/playlists/albums. Use *AD's API*.
2. Support windows now. 
3. Support NetEaseMusic MV download now.

#### Update:2018-05-17
1. Add new source from [QQMusic](http://y.qq.com) when the song not available with [NetEaseMusic](http://music.163.com).
2. Add new dependencies [FFMPEG](http://ffmpeg.org) for convert source from QQMusic with *.m4a* extension to *.mp3*.

#### Download:

1. **Clone project**

   ```shell
   git clone https://github.com/Kito0615/NetEaseMusic.git	
   ```

   Then you can run script(NetEaseMusic.py) in terminal with python3. Like:

   ```shell
   python3 NetEaseMusic.py
   ```

   or:

   ```shell
   chmod +x NetEaseMusic.py
   ./NetEaseMusic.py
   ```

2. **Download release**

   Click [here](https://github.com/Kito0615/NetEaseMusicDownloader/releases), download the version you need. Then you can run the binary file in terminal like:

   ```shell
   ./NetEaseMusic
   ```

   or copy the binary to `/usr/local/bin`, then you can execute the binary anywhere you want.

   ```shell
   copy NetEaseMusic /usr/local/bin
   NetEaseMusic
   ```

   ​

#### Usage:

There are a few ways to execute the binary when you copy to `/usr/local/bin`:

1. **Directly run command in terminal:**

   ```shell
   NetEaseMusic	
   ```

2. **Add the url follow the command:**

   ```shell
   NetEaseMusic [url]	
   ```

   This means download music from the following [url] page.

3. **Add the folder and the url follow the command :**

   ```shell
   NetEaseMusic [url] [folder]
   ```

   This means download music from the following [url] page to the destination [folder].

#### Envrionment:

[Python3.0+](https://www.python.org/downloads/mac-osx/) (with [*requests*](https://github.com/requests/requests) installed.)

[lame](http://lame.sourceforge.net) (use this lib to add Cover for audio.) [Here](https://github.com/Kito0615/NetEaseMusicDownloader/blob/master/Install_lame.md) is some instructions.

[Homebrew](https://brew.sh/) 

[License](https://github.com/Kito0615/NetEaseMusicDownloader/blob/master/MIT.md)

[FFMPEG](http://ffmpeg.org)

