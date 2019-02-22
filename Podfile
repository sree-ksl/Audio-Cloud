source 'https://github.com/BoseWCTC/Specs.git'

platform :ios, '11.4'
use_frameworks!
 
target "AudioCloud" do


    # pod 'ARCL', :git => 'https://github.com/aclima93/ARKit-CoreLocation.git', :branch => 'multi-subnode-distance-scaling'

	post_install do |installer|
		installer.pods_project.targets.each do |target|
			target.build_configurations.each do |config|
				config.build_settings['SWIFT_VERSION'] = '4.0'
			end
		end
	end
	
	# Required: This installs the core BoseWearable library.
	  pod 'BoseWearable', '~> 2.0'

	# Optional but recommended: This installs the UIKit search UI.
	  pod 'BoseWearable/SearchUI', '~> 2.0'

	end

end
