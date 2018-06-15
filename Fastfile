# This file contains the fastlane.tools configuration
# You can find the documentation at https://docs.fastlane.tools
#
# For a list of all available actions, check out
#
#     https://docs.fastlane.tools/actions
#
# For a list of all available plugins, check out
#
#     https://docs.fastlane.tools/plugins/available-plugins
#

# Uncomment the line if you want fastlane to automatically update itself
# update_fastlane

default_platform(:ios)

platform :ios do
  desc "自动化打包"
  lane :kmDebug do
    gym(
        scheme:"KMHealth-iPhone",
        export_method:"development",
        output_directory:"./fastlane/package",
        configuration:"Release",
        output_name:"KMHealth",
        clean:"true"
    )

    #firim(firim_api_token: "xxxx")

  end
end
