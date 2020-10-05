# maven2

###  制作方式
1. 安装
```bash
cd  dependency-installer
mi
```

2. 准备文件  

将已安装到本地的文件复制到项目根目录

3. 提交到github

### 使用方式:   
    添加如下内容到pom.xml  

```
  <repositories>
    <repository>
      <id>github-v49-maven2-repository</id>
      <name>github-v49-maven2-repository</name>
      <url>https://github.com/v49/maven2/raw/main/</url>
      <layout>default</layout>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
  </repositories>
```

