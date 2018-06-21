# weex android 最新依赖库，和淘宝保持一直，因为阿里暴露出来的依赖库版本太低
# 支持amreabi、armv7a、x86哦
# 集成方式 
``` java
root gradle添加:
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
依赖添加：
dependencies {
	        implementation 'com.github.zerochl:weex-android:0.18.5'
	}
```
# 想自己编译的注意了，CMake被我注释掉了，只能自行对比最新代码了
# 作者联系方式：QQ：975804495
# 疯狂的程序员群：186305789，没准你能遇到绝影大神
