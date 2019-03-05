### lib-agentwebx5
#### 使用说明：

`1.在项目gradlew中加入:`

```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

`2. 在使用的module中加入依赖`

```
dependencies {
	        implementation 'com.github.qd-remote-lib:lib-agentwebx5:1.3'
	}
```