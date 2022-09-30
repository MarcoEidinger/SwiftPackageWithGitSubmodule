# SwiftPackageWithGitSubmodule

This repository has a git submodule and I can confirm that SPM will initialize/update a git submodule if present in a Swift Package.

<img width="1727" alt="Screen Shot 2022-09-30 at 11 36 26 AM" src="https://user-images.githubusercontent.com/4176826/193336344-6a5716fa-c672-4dd6-8040-8fc746f8a1fd.png">

<img width="1370" alt="Screen Shot 2022-09-30 at 11 38 22 AM" src="https://user-images.githubusercontent.com/4176826/193336362-8d68f433-7d04-4d5c-8add-5f3672a5ba7b.png">

Note: I had cases that Xcode did not show the folder with the submodule content but content was available in respective checkout result stored in DerivedData folder (example: `~/Library/Developer/Xcode/DerivedData/AppUsingPackage-randomString/SourcePackages/checkouts/SwiftPackageWithGitSubmodule`).