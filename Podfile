# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

plugin 'cocoapods-sync-githooks'

target 'SyncGithooksDemo' do
end

abstract_target 'Githooks' do
  pod 'githooksA', git: 'https://github.com/dirtmelon/githooksA.git'
  pod 'githooksB', git: 'https://github.com/dirtmelon/githooksB.git'
end