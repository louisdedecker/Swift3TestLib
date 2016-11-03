source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.4'
use_frameworks!

target 'Swift3TestLib' do
	#pod "Mypod", :path => "/Users/admin/Dropbox/dev/swift/swift3/2016/testCreateCocoaPod/example0/Swift3TestLib/"
end 
 
post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '2.3'
    end
  end
End