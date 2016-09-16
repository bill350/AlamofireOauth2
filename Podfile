source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target 'Oauth2Test' do
    pod 'Alamofire', '~> 3.5.0'
    pod 'KeychainAccess', '~> 2.4.0'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |configuration|
      configuration.build_settings['SWIFT_VERSION'] = "2.3"
    end
  end
end
