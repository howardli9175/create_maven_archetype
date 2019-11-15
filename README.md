##准备
git

maven

##使用方法
### 1 拉取
```
git clone git@github.com:howardli9175/create_maven_archetype.git
git checkout tag_spark
```

### 2 本地安装archetype
```
cd create_maven_archetype
mvn install 
```

### 3 用archetype创建maven工程
```
mvn archetype:generate \
  -DarchetypeGroupId=com.howardli \
  -DarchetypeArtifactId=spark_archetype \
  -DarchetypeVersion=1.0.0 \
  -DgroupId=com.howardli \
  -DartifactId=testbb \
  -Dversion=1.0.0 \
  -Dpackage=def
```