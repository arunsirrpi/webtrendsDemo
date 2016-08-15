source 'https://github.com/CocoaPods/Specs.git'

use_frameworks!
platform :ios, '8.0'

def all_pods
  pod 'Flurry-iOS-SDK/FlurrySDK', '7.6.6'
  pod 'Webtrends-SDK/Core', '3.0.14'
end


target 'WebtrendsInsideFramework' do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for WebtrendsInsideFramework
  all_pods

  target 'WebtrendsInsideFrameworkTests' do
    inherit! :search_paths
    all_pods
  end

end


