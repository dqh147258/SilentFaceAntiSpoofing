该项目为[小视科技](https://www.minivision.cn/)的静默活体检测算法在安卓平台的部署代码。

<img src="https://github.com/minivision-ai/Silent-Face-Anti-Spoofing/blob/master/images/demo.gif" width="300" height="400"/>

由于小视科技没有给出maven依赖,所以fork一个来方便做maven依赖.

项目源地址
[https://github.com/minivision-ai/Silent-Face-Anti-Spoofing-APK](https://github.com/minivision-ai/Silent-Face-Anti-Spoofing-APK)

---

依赖

[![](https://www.jitpack.io/v/dqh147258/SilentFaceAntiSpoofing.svg)](https://www.jitpack.io/#dqh147258/SilentFaceAntiSpoofing)

```
	allprojects {
		repositories {
			//...
			maven { url 'https://www.jitpack.io' }
		}
	}
```

```
	dependencies {
	        implementation 'com.github.dqh147258:SilentFaceAntiSpoofing:1.+'
	}
```
