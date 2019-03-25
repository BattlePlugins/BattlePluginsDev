# BattlePluginsDev
Maven &amp; Git submodules for easy installation:
```
git clone --recurse-submodules https://github.com/BattlePlugins/BattlePluginsDev.git
mvn install -f setup.xml
mvn -B archetype:generate -DarchetypeGroupId=mc.bp -DarchetypeArtifactId=server -DarchetypeVersion=test
git checkout -- pom.xml
mvn clean install`
```
