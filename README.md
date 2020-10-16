# flutter_rtmp

```
environment:
  sdk: ">=2.1.0 <3.0.0"
  flutter: ">=1.10.0"
```

## Instructions
> **It is recommended to follow the tag/release version number when installing and using git**

### [Update 0.1.6](https://github.com/MEnigma/flutter_rtmp/blob/master/CHANGELOG.md)


### Introduction
#### 1. The first method
    flutter_rtmp:
       git: https://github.com/MEnigma/flutter_rtmp.git
       ref: ***

#### 2. The second
    flutter_rtmp: ^*.*.*

#### About iOS configuration
```
Need to be added in info.plist

<key>io.flutter.embedded_views_preview</key>
<true/>
```
#### About Android configuration
```
No need to configure
```

>Example
> ```
> /// Controller
> void initState() {
> super.initState();
> _manager = RtmpManager();
>}
>
> /// View
> Widget build(BuildContext context) {
>
> return RtmpView(
> manager: _manager,
> );
>}
> ```
    
### Quote

>* iOS use [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit)
>* Use [yasea] in android(https://github.com/begeekmyfriend/yasea)

### Progress

* [x] Push stream
* [x] Switch camera
* [] Beauty
* [] Rotate


### [LICENSE](https://github.com/MEnigma/flutter_rtmp/blob/master/LICENSE)

* Participants
>* mark <https://github.com/MEnigma>
>* youshinki <https://github.com/youshinki>

### Versions
##### [Update Log](https://github.com/MEnigma/flutter_rtmp/blob/master/CHANGELOG.md)
* [0.1.6.1](https://github.com/MEnigma/flutter_rtmp/tree/v0.1.6.1)
* [0.1.6](https://github.com/MEnigma/flutter_rtmp/tree/v0.1.6)
* [0.1.4](https://github.com/MEnigma/flutter_rtmp/tree/v0.1.4)
