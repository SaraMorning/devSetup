## 下载
https://gradle.org/releases/

## 配置下载依赖仓库
```json
    repositories {
        mavenLocal()
        maven{ url 'http://maven.aliyun.com/nexus/content/repositories/jcenter'}
        maven{ url 'http://maven.aliyun.com/nexus/content/groups/public/' }
        maven{ url 'https://maven.aliyun.com/repository/gradle-plugin' }
        maven{ url 'https://maven.aliyun.com/repository/google' }
    }
```