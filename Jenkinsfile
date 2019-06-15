library identifier: 'BattlePipelineLib@master', retriever: modernSCM(
    [$class: 'GitSCMSource',
     remote: 'https://github.com/BattlePlugins/BattlePipelineLib',
     credentialsId: 'github-login'])

deployJarToMaven {
    repo = 'BattlePluginsDev'
    libPath = 'lib/'
}