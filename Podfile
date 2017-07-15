# Uncomment the next line to define a global platform for your project
 platform :ios, '10.3'

target 'meh' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for meh
  pod 'Caffe2Kit', :git => 'git://github.com/RobertBiehl/caffe2-ios'

post_install do |installer|
installer.pods_project.targets.each do |target|
target.build_configurations.each do |config|
config.build_settings['ENABLE_BITCODE'] = 'NO'
end
end
end

  target 'mehTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'mehUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
