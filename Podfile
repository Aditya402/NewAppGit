# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'MyNewAppGit' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
pod 'AFNetworking'
  # Pods for MyNewAppGit

  target 'MyNewAppGitTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'MyNewAppGitUITests' do
    # Pods for testing
  end

end
post_install do |installer|
  installer.pods_project.targets.each do |target|
    puts "#{target.name}"
  end
end
