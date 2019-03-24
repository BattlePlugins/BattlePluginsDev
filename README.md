# BattlePluginsDev
Maven &amp; Git submodules for easy installation:
```
git clone --recurse-submodules https://github.com/BattlePlugins/BattlePluginsDev.git
mvn install -f setup.xml
mvn archetype:generate -DgroupId=mc.battleplugins.dev -DartifactId=server -Dversion=test
mvn clean install`
```
