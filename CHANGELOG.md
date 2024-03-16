# Changelog

## [Unreleased](https://github.com/skywinder/ActionSheetPicker-3.0/tree/HEAD)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.7.3...HEAD)

**Merged pull requests:**

- add Wei18 as a contributor for infra, review, and maintenance [\#572](https://github.com/skywinder/ActionSheetPicker-3.0/pull/572) ([allcontributors[bot]](https://github.com/apps/allcontributors))
- Update CONTRIBUTING.md [\#553](https://github.com/skywinder/ActionSheetPicker-3.0/pull/553) ([noorulain17](https://github.com/noorulain17))

## [2.7.3](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.7.3) (2024-02-05)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.7.2...2.7.3)

**Closed issues:**

- Need secrets.COCOAPODS\_TRUNK\_TOKEN [\#565](https://github.com/skywinder/ActionSheetPicker-3.0/issues/565)
- SWActionSheetVC.dismissTap prevents calendar from working in inline style [\#532](https://github.com/skywinder/ActionSheetPicker-3.0/issues/532)
- iOS build error while using carthage update [\#472](https://github.com/skywinder/ActionSheetPicker-3.0/issues/472)

**Merged pull requests:**

- Update ActionSheetPicker-3.0.podspec to 2.7.3 [\#568](https://github.com/skywinder/ActionSheetPicker-3.0/pull/568) ([Wei18](https://github.com/Wei18))
- Add job build in ci.yml for CocoaPods, Carthage, Swift Package [\#567](https://github.com/skywinder/ActionSheetPicker-3.0/pull/567) ([Wei18](https://github.com/Wei18))
- Fixed DeployCocoaPods Github Action [\#566](https://github.com/skywinder/ActionSheetPicker-3.0/pull/566) ([Wei18](https://github.com/Wei18))
- Add GitHub actions to deploy CocoaPods [\#564](https://github.com/skywinder/ActionSheetPicker-3.0/pull/564) ([Wei18](https://github.com/Wei18))
- Fix date picker dismissing when tapping on date picker in .inline style [\#551](https://github.com/skywinder/ActionSheetPicker-3.0/pull/551) ([joeboyscout04](https://github.com/joeboyscout04))
- Migrate CI from TravisCI to GitHubActions [\#546](https://github.com/skywinder/ActionSheetPicker-3.0/pull/546) ([Econa77](https://github.com/Econa77))

## [2.7.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.7.2) (2024-01-30)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.7.1...2.7.2)

**Fixed bugs:**

- Current date is not available on compact Date picker style iOS 14.4 & above [\#534](https://github.com/skywinder/ActionSheetPicker-3.0/issues/534)
- tapDismissAction broken after 2.5.1 [\#526](https://github.com/skywinder/ActionSheetPicker-3.0/issues/526)

**Closed issues:**

- Unable to build archieve on Xcode 14.3 [\#558](https://github.com/skywinder/ActionSheetPicker-3.0/issues/558)
- SPM Issues [\#554](https://github.com/skywinder/ActionSheetPicker-3.0/issues/554)
- ActionSheet opens in wrong display when iphone is connected to an external display. [\#548](https://github.com/skywinder/ActionSheetPicker-3.0/issues/548)
- Picker not showing on iPad but only on iPhone [\#540](https://github.com/skywinder/ActionSheetPicker-3.0/issues/540)
- Remove the pieces of the code for less than the Deployment Target [\#538](https://github.com/skywinder/ActionSheetPicker-3.0/issues/538)
- Not working with Swift Package Manager \[bug\] [\#537](https://github.com/skywinder/ActionSheetPicker-3.0/issues/537)
- "exported: true has no effect in '\_specialize' attribute" Issue at Xcode 12.5 [\#536](https://github.com/skywinder/ActionSheetPicker-3.0/issues/536)
- Data Linkage with ActionSheetMultipleStringPicker [\#529](https://github.com/skywinder/ActionSheetPicker-3.0/issues/529)
- Cannot use the library if is installed using Swift Package Manager [\#525](https://github.com/skywinder/ActionSheetPicker-3.0/issues/525)
- Minimum iOS version [\#522](https://github.com/skywinder/ActionSheetPicker-3.0/issues/522)

**Merged pull requests:**

- Release 2.7.2 [\#562](https://github.com/skywinder/ActionSheetPicker-3.0/pull/562) ([Wei18](https://github.com/Wei18))
- \[Fix\] import issue on Swift Pacakge [\#555](https://github.com/skywinder/ActionSheetPicker-3.0/pull/555) ([Wei18](https://github.com/Wei18))
- Fixed an issue building using the Swift Package Manager [\#545](https://github.com/skywinder/ActionSheetPicker-3.0/pull/545) ([Econa77](https://github.com/Econa77))
- Issue 538 - Remove conditional statements less than iOS9 [\#539](https://github.com/skywinder/ActionSheetPicker-3.0/pull/539) ([jolyot](https://github.com/jolyot))
- Fixed \#526 \(`tapDismissAction` broken after 2.5.1\), Improved \#491 \(Background-tap to dismiss\) [\#528](https://github.com/skywinder/ActionSheetPicker-3.0/pull/528) ([noorulain17](https://github.com/noorulain17))
- Fix SPM issue \(\#525\) [\#527](https://github.com/skywinder/ActionSheetPicker-3.0/pull/527) ([ghost](https://github.com/ghost))
- Reduced minimum iOS version back to 9.0 [\#523](https://github.com/skywinder/ActionSheetPicker-3.0/pull/523) ([ddaddy](https://github.com/ddaddy))
- Fix typo in the comment [\#521](https://github.com/skywinder/ActionSheetPicker-3.0/pull/521) ([ad-sho-loko](https://github.com/ad-sho-loko))

## [2.7.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.7.1) (2020-10-26)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.6.1...2.7.1)

**Implemented enhancements:**

- Use with inputView [\#266](https://github.com/skywinder/ActionSheetPicker-3.0/issues/266)

**Fixed bugs:**

- Presenting picker fails when picker is presented within modally presented view controller on iPad \(iOS 13.7\) with ActionSheetPicker version 2.6.1. [\#513](https://github.com/skywinder/ActionSheetPicker-3.0/issues/513)

**Closed issues:**

- SPM: Cannot find type 'ActionSheetStringPicker' in scope [\#512](https://github.com/skywinder/ActionSheetPicker-3.0/issues/512)
- iOS 14 unable to select date in inline datePickerStyle [\#505](https://github.com/skywinder/ActionSheetPicker-3.0/issues/505)
- Wrong format specifier in example [\#344](https://github.com/skywinder/ActionSheetPicker-3.0/issues/344)

**Merged pull requests:**

- update settings [\#520](https://github.com/skywinder/ActionSheetPicker-3.0/pull/520) ([skywinder](https://github.com/skywinder))
- Present picker on topViewController instead of rootViewController [\#519](https://github.com/skywinder/ActionSheetPicker-3.0/pull/519) ([noorulain17](https://github.com/noorulain17))
- Issue 344 - Fixed typo in ReadMe for Objective C - NSInteger [\#518](https://github.com/skywinder/ActionSheetPicker-3.0/pull/518) ([noorulain17](https://github.com/noorulain17))
- Issue 512 - Fixed SPM file scope/path issues [\#517](https://github.com/skywinder/ActionSheetPicker-3.0/pull/517) ([noorulain17](https://github.com/noorulain17))
- Add Swift Package Manager instruction [\#516](https://github.com/skywinder/ActionSheetPicker-3.0/pull/516) ([cutmail](https://github.com/cutmail))
- Issue \#505: iOS 14 unable to select date in inline datePickerStyle [\#514](https://github.com/skywinder/ActionSheetPicker-3.0/pull/514) ([palmtrae](https://github.com/palmtrae))

## [2.6.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.6.1) (2020-10-07)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.6.0...2.6.1)

**Implemented enhancements:**

- update deprecated classes: UIPopoverPresentationController [\#499](https://github.com/skywinder/ActionSheetPicker-3.0/pull/499) ([cutmail](https://github.com/cutmail))

**Fixed bugs:**

- iOS14 datepicker style looks pretty bad! [\#500](https://github.com/skywinder/ActionSheetPicker-3.0/issues/500)

**Closed issues:**

- Date Picker Wheels Not Showing Anymore on iOS 14 [\#510](https://github.com/skywinder/ActionSheetPicker-3.0/issues/510)
- carthage update fails for "2.6.0", is successful for "2.5.1". [\#507](https://github.com/skywinder/ActionSheetPicker-3.0/issues/507)
- iOS 14 datePicker not centered horizontally [\#506](https://github.com/skywinder/ActionSheetPicker-3.0/issues/506)
- Swift Package Manager [\#426](https://github.com/skywinder/ActionSheetPicker-3.0/issues/426)

**Merged pull requests:**

- Bottom padding for iPhone X style phones [\#511](https://github.com/skywinder/ActionSheetPicker-3.0/pull/511) ([palmtrae](https://github.com/palmtrae))
- Fixed carthage build for Xcode \<12 [\#508](https://github.com/skywinder/ActionSheetPicker-3.0/pull/508) ([ddaddy](https://github.com/ddaddy))

## [2.6.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.6.0) (2020-09-27)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.5.1...2.6.0)

**Fixed bugs:**

- Memory leaks when using ActionSheetDatePicker on a modally presented UIViewController [\#358](https://github.com/skywinder/ActionSheetPicker-3.0/issues/358)

**Closed issues:**

- ActionSheetDatePicker still crash in Xcode12 when set the datePickerStyle  [\#498](https://github.com/skywinder/ActionSheetPicker-3.0/issues/498)
- How to click on the Background,dismiss the picker [\#491](https://github.com/skywinder/ActionSheetPicker-3.0/issues/491)
- Deprecated UIPopoverController API when targeting iOS 9 [\#296](https://github.com/skywinder/ActionSheetPicker-3.0/issues/296)
- TapActionCancel Error [\#269](https://github.com/skywinder/ActionSheetPicker-3.0/issues/269)

**Merged pull requests:**

- udpate recommended settings, fixed warrings [\#504](https://github.com/skywinder/ActionSheetPicker-3.0/pull/504) ([skywinder](https://github.com/skywinder))
- Fixed target for SPM - Package.swift file [\#503](https://github.com/skywinder/ActionSheetPicker-3.0/pull/503) ([noorulain17](https://github.com/noorulain17))
- iOS 14 default datePickerStyle = wheels when not set in the app, Fixes Issue \#491 \(Background tap\) [\#502](https://github.com/skywinder/ActionSheetPicker-3.0/pull/502) ([noorulain17](https://github.com/noorulain17))
- Updated contributers list [\#497](https://github.com/skywinder/ActionSheetPicker-3.0/pull/497) ([noorulain17](https://github.com/noorulain17))

## [2.5.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.5.1) (2020-09-01)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.5.0...2.5.1)

**Closed issues:**

- Date picker on iOS 14 [\#492](https://github.com/skywinder/ActionSheetPicker-3.0/issues/492)
- Action sheet reappears after pressing Done [\#476](https://github.com/skywinder/ActionSheetPicker-3.0/issues/476)
- ActionSheetPicker popover selection is not working for iPad on iOS 11+ [\#384](https://github.com/skywinder/ActionSheetPicker-3.0/issues/384)

**Merged pull requests:**

- Added iOS 14 DatePickerStyle Support [\#488](https://github.com/skywinder/ActionSheetPicker-3.0/pull/488) ([noorulain17](https://github.com/noorulain17))

## [2.5.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.5.0) (2020-04-30)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.11...2.5.0)

**Closed issues:**

- Example causes EXC\_BAD\_ACCESS \(fix\) [\#336](https://github.com/skywinder/ActionSheetPicker-3.0/issues/336)

**Merged pull requests:**

- Added Xcode 11.x compatibility & DarkMode support [\#479](https://github.com/skywinder/ActionSheetPicker-3.0/pull/479) ([noorulain17](https://github.com/noorulain17))

## [2.4.11](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.11) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.9...2.4.11)

## [2.4.9](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.9) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.8...2.4.9)

## [2.4.8](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.8) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.7...2.4.8)

## [2.4.7](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.7) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.6...2.4.7)

## [2.4.6](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.6) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.5...2.4.6)

## [2.4.5](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.5) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.4...2.4.5)

## [2.4.4](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.4) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.3...2.4.4)

## [2.4.3](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.3) (2020-02-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.2...2.4.3)

**Closed issues:**

- Swift 4.2 [\#401](https://github.com/skywinder/ActionSheetPicker-3.0/issues/401)
- Swift 4  [\#363](https://github.com/skywinder/ActionSheetPicker-3.0/issues/363)
- Swift 3.0/ Xcode 8 support  [\#318](https://github.com/skywinder/ActionSheetPicker-3.0/issues/318)

## [2.4.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.2) (2020-02-12)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.1...2.4.2)

**Fixed bugs:**

- \[BUG\] - HIGH - Not working on screen rotation + Not working in Landscape [\#460](https://github.com/skywinder/ActionSheetPicker-3.0/issues/460)

**Closed issues:**

- Dynamic width adjusting to text size in picker [\#162](https://github.com/skywinder/ActionSheetPicker-3.0/issues/162)

**Merged pull requests:**

- Fix rotation issues. [\#468](https://github.com/skywinder/ActionSheetPicker-3.0/pull/468) ([skywinder](https://github.com/skywinder))
- Update source patterns [\#458](https://github.com/skywinder/ActionSheetPicker-3.0/pull/458) ([ElfSundae](https://github.com/ElfSundae))

## [2.4.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.1) (2019-12-24)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.4.0...2.4.1)

**Implemented enhancements:**

- Allow use of attributed strings as picker row titles [\#341](https://github.com/skywinder/ActionSheetPicker-3.0/issues/341)

**Fixed bugs:**

- iOS 13 SDK Conditional Compilation [\#453](https://github.com/skywinder/ActionSheetPicker-3.0/issues/453)

**Closed issues:**

- Xcode 11 can not run successfully, ActionSheetPicker-3.0 version \(2.4.0\) ,use cocoaPods [\#454](https://github.com/skywinder/ActionSheetPicker-3.0/issues/454)

**Merged pull requests:**

- Add Discord link and fix some minor issues in README.md file [\#456](https://github.com/skywinder/ActionSheetPicker-3.0/pull/456) ([andreabusi](https://github.com/andreabusi))
- Fix podspec [\#455](https://github.com/skywinder/ActionSheetPicker-3.0/pull/455) ([ElfSundae](https://github.com/ElfSundae))
- Improve Markdown syntax several .md files [\#452](https://github.com/skywinder/ActionSheetPicker-3.0/pull/452) ([andreabusi](https://github.com/andreabusi))

## [2.4.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.4.0) (2019-12-10)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.3.1...2.4.0)

**Fixed bugs:**

- Is here have retain cycle? [\#428](https://github.com/skywinder/ActionSheetPicker-3.0/issues/428)
- ActionSheetPicker values are not being displayed on iPhone on iOS 13 [\#427](https://github.com/skywinder/ActionSheetPicker-3.0/issues/427)
- \#picker ui not showing properly on ios 13 ipad [\#422](https://github.com/skywinder/ActionSheetPicker-3.0/issues/422)
- SupportedInterfaceOrientations Horizontal fixed [\#398](https://github.com/skywinder/ActionSheetPicker-3.0/issues/398)
- ActionSheetStringPicker not working on iPad \(only iPhone\) [\#156](https://github.com/skywinder/ActionSheetPicker-3.0/issues/156)
- Supported interface orientations fix [\#399](https://github.com/skywinder/ActionSheetPicker-3.0/pull/399) ([moheny](https://github.com/moheny))

**Closed issues:**

- Not working in iPad [\#420](https://github.com/skywinder/ActionSheetPicker-3.0/issues/420)

**Merged pull requests:**

- Add contributorsi & update readme [\#451](https://github.com/skywinder/ActionSheetPicker-3.0/pull/451) ([skywinder](https://github.com/skywinder))
- docs: add TimCinel as a contributor [\#449](https://github.com/skywinder/ActionSheetPicker-3.0/pull/449) ([allcontributors[bot]](https://github.com/apps/allcontributors))
- docs: add xjki as a contributor [\#448](https://github.com/skywinder/ActionSheetPicker-3.0/pull/448) ([allcontributors[bot]](https://github.com/apps/allcontributors))
- Clean up of outdated projects [\#447](https://github.com/skywinder/ActionSheetPicker-3.0/pull/447) ([skywinder](https://github.com/skywinder))

## [2.3.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.3.1) (2019-12-08)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.3.0...2.3.1)

**Fixed bugs:**

- not support dark mode on iOS 13 [\#424](https://github.com/skywinder/ActionSheetPicker-3.0/issues/424)
- fix iOS 13 popover layout \(toolbar cut\) [\#444](https://github.com/skywinder/ActionSheetPicker-3.0/pull/444) ([Bino90](https://github.com/Bino90))
- Fix leaked memory when present Popoverview on iPad [\#404](https://github.com/skywinder/ActionSheetPicker-3.0/pull/404) ([vinhtnk](https://github.com/vinhtnk))

**Closed issues:**

- Adding actionsheet date picker on uitableview cell class doesn't dismiss it when pressing done [\#419](https://github.com/skywinder/ActionSheetPicker-3.0/issues/419)
- ActionSheetStringPicker [\#418](https://github.com/skywinder/ActionSheetPicker-3.0/issues/418)
- close  [\#402](https://github.com/skywinder/ActionSheetPicker-3.0/issues/402)
- Not able to set Arabic text on Cancel and Done Button of ActionSheetStringPicker [\#389](https://github.com/skywinder/ActionSheetPicker-3.0/issues/389)
- Crash if the parent becomes a zombie [\#388](https://github.com/skywinder/ActionSheetPicker-3.0/issues/388)
- How to add border to the UIToolbar [\#382](https://github.com/skywinder/ActionSheetPicker-3.0/issues/382)
- clang: error: -fobjc-weak is not supported on the current deployment target [\#380](https://github.com/skywinder/ActionSheetPicker-3.0/issues/380)
- iOS 10 custom cancel and done buttons do not appear [\#376](https://github.com/skywinder/ActionSheetPicker-3.0/issues/376)
- Customise rowHeightForComponent [\#374](https://github.com/skywinder/ActionSheetPicker-3.0/issues/374)

**Merged pull requests:**

- CLI allcontributors setup [\#442](https://github.com/skywinder/ActionSheetPicker-3.0/pull/442) ([skywinder](https://github.com/skywinder))
- xcode updates with missing variables [\#434](https://github.com/skywinder/ActionSheetPicker-3.0/pull/434) ([skywinder](https://github.com/skywinder))
- should use  “weak” [\#429](https://github.com/skywinder/ActionSheetPicker-3.0/pull/429) ([xiaoer371](https://github.com/xiaoer371))
- Add iOS 13 support - Handle UIWindow for iOS 13 changes [\#425](https://github.com/skywinder/ActionSheetPicker-3.0/pull/425) ([andreabusi](https://github.com/andreabusi))
- Support iOS 13 Dark Mode [\#421](https://github.com/skywinder/ActionSheetPicker-3.0/pull/421) ([arnoldxt](https://github.com/arnoldxt))
- Attributed strings can be used as picker rows. Fixed accessibility for picker title. [\#403](https://github.com/skywinder/ActionSheetPicker-3.0/pull/403) ([xjki](https://github.com/xjki))
- Fix run ActionSheetPickerTests on Xcode and Travis CI [\#393](https://github.com/skywinder/ActionSheetPicker-3.0/pull/393) ([nowsprinting](https://github.com/nowsprinting))

## [2.3.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.3.0) (2017-11-21)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.2.0...2.3.0)

**Implemented enhancements:**

- Change font in Multiple String picker [\#343](https://github.com/skywinder/ActionSheetPicker-3.0/pull/343) ([ricardohg](https://github.com/ricardohg))
- Add option to customise window level presentation [\#299](https://github.com/skywinder/ActionSheetPicker-3.0/pull/299) ([tbaranes](https://github.com/tbaranes))

**Closed issues:**

- unknown error -1=ffffffffffffffff Command /bin/sh failed with exit code 1 [\#369](https://github.com/skywinder/ActionSheetPicker-3.0/issues/369)
- App crashes in iOS 11 [\#360](https://github.com/skywinder/ActionSheetPicker-3.0/issues/360)
- App crash when setTableFooterView [\#345](https://github.com/skywinder/ActionSheetPicker-3.0/issues/345)
- Warnings in Xcode 8.3 \(Swift 3.1\) [\#339](https://github.com/skywinder/ActionSheetPicker-3.0/issues/339)
- iPad problem [\#338](https://github.com/skywinder/ActionSheetPicker-3.0/issues/338)
- Date Picker not working in IOS 8.2 swift 3 [\#334](https://github.com/skywinder/ActionSheetPicker-3.0/issues/334)
- Change value of picker programmatically  [\#333](https://github.com/skywinder/ActionSheetPicker-3.0/issues/333)
- Date picker example [\#332](https://github.com/skywinder/ActionSheetPicker-3.0/issues/332)
- Change time format to "HH:mm" for time picker [\#327](https://github.com/skywinder/ActionSheetPicker-3.0/issues/327)
- UIDatePicker not shows correct date [\#302](https://github.com/skywinder/ActionSheetPicker-3.0/issues/302)
- Swift 3.0 Migration [\#293](https://github.com/skywinder/ActionSheetPicker-3.0/issues/293)
- DEPRECATED\_MSG\_ATTRIBUTE [\#234](https://github.com/skywinder/ActionSheetPicker-3.0/issues/234)

**Merged pull requests:**

- Fixing tint color issue in toolbar [\#366](https://github.com/skywinder/ActionSheetPicker-3.0/pull/366) ([yapiskan](https://github.com/yapiskan))
- Fixes documentation [\#352](https://github.com/skywinder/ActionSheetPicker-3.0/pull/352) ([ykws](https://github.com/ykws))
- Update Readme for Swift 3 and fixing indexes / values [\#319](https://github.com/skywinder/ActionSheetPicker-3.0/pull/319) ([VincentNarbot](https://github.com/VincentNarbot))
- Fix highlight ReadME [\#309](https://github.com/skywinder/ActionSheetPicker-3.0/pull/309) ([ezefranca](https://github.com/ezefranca))

## [2.2.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.2.0) (2016-06-27)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.1.0...2.2.0)

**Implemented enhancements:**

- Change tint color / font color of Done / Cancel buttons [\#54](https://github.com/skywinder/ActionSheetPicker-3.0/issues/54)

**Merged pull requests:**

- add ability to set toolbar buttons color [\#288](https://github.com/skywinder/ActionSheetPicker-3.0/pull/288) ([skywinder](https://github.com/skywinder))
- Add ability to set toolbar color via toolbarBackgroundColor property [\#287](https://github.com/skywinder/ActionSheetPicker-3.0/pull/287) ([skywinder](https://github.com/skywinder))
- Add method to set text color: `setTextColor` [\#286](https://github.com/skywinder/ActionSheetPicker-3.0/pull/286) ([skywinder](https://github.com/skywinder))
- Blur effect readme [\#284](https://github.com/skywinder/ActionSheetPicker-3.0/pull/284) ([nikola-mladenovic](https://github.com/nikola-mladenovic))
- Adding the ability to disable popover behavior on iPad per picker instance [\#278](https://github.com/skywinder/ActionSheetPicker-3.0/pull/278) ([airdrummingfool](https://github.com/airdrummingfool))

## [2.1.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.1.0) (2016-05-19)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.0.5...2.1.0)

**Closed issues:**

- Import statement outdated on Swift-example [\#261](https://github.com/skywinder/ActionSheetPicker-3.0/issues/261)

**Merged pull requests:**

- This commit resolves \#261 [\#262](https://github.com/skywinder/ActionSheetPicker-3.0/pull/262) ([guillosaracco](https://github.com/guillosaracco))
- Fixes \#205 Add blur feature for picker background [\#251](https://github.com/skywinder/ActionSheetPicker-3.0/pull/251) ([nikola-mladenovic](https://github.com/nikola-mladenovic))

## [2.0.5](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.0.5) (2016-02-08)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.0.4...2.0.5)

**Closed issues:**

- Issue in origin [\#245](https://github.com/skywinder/ActionSheetPicker-3.0/issues/245)
- NSRangeException occurs when I try to fast scroll \(apparently not selecting anything\) and click done [\#229](https://github.com/skywinder/ActionSheetPicker-3.0/issues/229)
- Picker is duplicated when use showActionSheetPicker [\#224](https://github.com/skywinder/ActionSheetPicker-3.0/issues/224)
- ActionSheetPickerCustomPickerDelegate [\#214](https://github.com/skywinder/ActionSheetPicker-3.0/issues/214)
- ActionSheetDatePicker iOS 9 Problems [\#213](https://github.com/skywinder/ActionSheetPicker-3.0/issues/213)
- Blur instead of semi transparent black overlay [\#205](https://github.com/skywinder/ActionSheetPicker-3.0/issues/205)

**Merged pull requests:**

- Fix Swift Bug RE self.initialSelection in multi-pickers [\#252](https://github.com/skywinder/ActionSheetPicker-3.0/pull/252) ([sschale](https://github.com/sschale))

## [2.0.4](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.0.4) (2015-12-04)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.0.3...2.0.4)

**Closed issues:**

- ActionSheetStringPicker problem with simulator and device iOS9 [\#233](https://github.com/skywinder/ActionSheetPicker-3.0/issues/233)
- ActionSheetPickerView  Picker View not appearing for iPAD [\#187](https://github.com/skywinder/ActionSheetPicker-3.0/issues/187)
- Date Picker not aligned well on landscape iPhone 6 Plus [\#129](https://github.com/skywinder/ActionSheetPicker-3.0/issues/129)

**Merged pull requests:**

- Use modern objective c initializer syntax [\#235](https://github.com/skywinder/ActionSheetPicker-3.0/pull/235) ([mamnun](https://github.com/mamnun))
- Fixes presentation issue on iPads [\#131](https://github.com/skywinder/ActionSheetPicker-3.0/pull/131) ([maciekish](https://github.com/maciekish))

## [2.0.3](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.0.3) (2015-10-13)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.0.2...2.0.3)

**Merged pull requests:**

- A UIView contain no text rather than nil should be returned … [\#221](https://github.com/skywinder/ActionSheetPicker-3.0/pull/221) ([ainopara](https://github.com/ainopara))

## [2.0.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.0.2) (2015-10-08)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.0.1...2.0.2)

**Implemented enhancements:**

- make font of picker label ready for customize. [\#218](https://github.com/skywinder/ActionSheetPicker-3.0/pull/218) ([ainopara](https://github.com/ainopara))

## [2.0.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.0.1) (2015-09-17)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/2.0.0...2.0.1)

**Fixed bugs:**

- Added missing header reference [\#212](https://github.com/skywinder/ActionSheetPicker-3.0/pull/212) ([donshefer](https://github.com/donshefer))

## [2.0.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/2.0.0) (2015-09-16)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.7.2...2.0.0)

**Closed issues:**

- Xcode 7 beta and Swift 2.0 [\#185](https://github.com/skywinder/ActionSheetPicker-3.0/issues/185)

**Merged pull requests:**

- Swift 2.0 update [\#211](https://github.com/skywinder/ActionSheetPicker-3.0/pull/211) ([skywinder](https://github.com/skywinder))

## [1.7.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.7.2) (2015-09-01)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.7.1...1.7.2)

**Implemented enhancements:**

- Work-around for iOS 9 split view multi-tasking [\#199](https://github.com/skywinder/ActionSheetPicker-3.0/pull/199) ([kashifhisam](https://github.com/kashifhisam))

**Fixed bugs:**

- Picker rotating when host view controller fixed to portrait [\#100](https://github.com/skywinder/ActionSheetPicker-3.0/issues/100)

**Merged pull requests:**

- Keep app's interface orientation rules [\#206](https://github.com/skywinder/ActionSheetPicker-3.0/pull/206) ([tbaranes](https://github.com/tbaranes))

## [1.7.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.7.1) (2015-08-24)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.7.0...1.7.1)

**Fixed bugs:**

- Picker presenting problems on iOS 9 within multitasking-splitview in compact size  [\#194](https://github.com/skywinder/ActionSheetPicker-3.0/issues/194)

**Merged pull requests:**

- make setPickerBackgroundColor work in iPad. [\#200](https://github.com/skywinder/ActionSheetPicker-3.0/pull/200) ([ainopara](https://github.com/ainopara))
- ActionSheetMultipleStringsPicker [\#196](https://github.com/skywinder/ActionSheetPicker-3.0/pull/196) ([perezpaya](https://github.com/perezpaya))

## [1.7.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.7.0) (2015-07-21)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.6.2...1.7.0)

**Implemented enhancements:**

- Dark Mode [\#102](https://github.com/skywinder/ActionSheetPicker-3.0/issues/102)
- Add methods to custom background color ... [\#195](https://github.com/skywinder/ActionSheetPicker-3.0/pull/195) ([ainopara](https://github.com/ainopara))

## [1.6.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.6.2) (2015-05-07)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.6.1...1.6.2)

**Fixed bugs:**

- TapAction calls the wrong method \(on iOS 7 only\) [\#173](https://github.com/skywinder/ActionSheetPicker-3.0/issues/173)

**Merged pull requests:**

- Fix tapDismissAction bug in iOS7 [\#176](https://github.com/skywinder/ActionSheetPicker-3.0/pull/176) ([foxluqi](https://github.com/foxluqi))

## [1.6.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.6.1) (2015-04-17)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.6.0...1.6.1)

**Implemented enhancements:**

- Carthage support [\#171](https://github.com/skywinder/ActionSheetPicker-3.0/issues/171)

## [1.6.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.6.0) (2015-04-17)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.5.1...1.6.0)

**Implemented enhancements:**

- Integration ActionSheetPicker as dynamic framework [\#170](https://github.com/skywinder/ActionSheetPicker-3.0/issues/170)
- Cancel Action unknow for `ActionSheetDistancePicker` [\#166](https://github.com/skywinder/ActionSheetPicker-3.0/issues/166)
- iOS 5.1.1 compatibility added [\#164](https://github.com/skywinder/ActionSheetPicker-3.0/pull/164) ([kashifhisam](https://github.com/kashifhisam))
- Added "tag" to AbstractActionSheet [\#159](https://github.com/skywinder/ActionSheetPicker-3.0/pull/159) ([Jeepston](https://github.com/Jeepston))

**Merged pull requests:**

- Exposed ActionSheet and created intVar for better config. [\#160](https://github.com/skywinder/ActionSheetPicker-3.0/pull/160) ([zecmo](https://github.com/zecmo))

## [1.5.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.5.1) (2015-03-27)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.5.0...1.5.1)

**Fixed bugs:**

- iOS 8 - iPad - UISplitViewController issue. [\#157](https://github.com/skywinder/ActionSheetPicker-3.0/issues/157)

**Closed issues:**

- iOS 7.1 done button requires long press [\#167](https://github.com/skywinder/ActionSheetPicker-3.0/issues/167)

## [1.5.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.5.0) (2015-03-05)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.4.0...1.5.0)

**Closed issues:**

- upside down portrait mode displays incorrectly [\#146](https://github.com/skywinder/ActionSheetPicker-3.0/issues/146)

**Merged pull requests:**

- Added support for upside down portrait; [\#149](https://github.com/skywinder/ActionSheetPicker-3.0/pull/149) ([dtrauger](https://github.com/dtrauger))

## [1.4.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.4.0) (2015-03-05)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.13...1.4.0)

**Implemented enhancements:**

- ActionSheetDistancePicker + Swift usage [\#139](https://github.com/skywinder/ActionSheetPicker-3.0/issues/139)

**Closed issues:**

- Dismiss action sheet by tapping on background [\#80](https://github.com/skywinder/ActionSheetPicker-3.0/issues/80)

**Merged pull requests:**

- Add additional showPickerWithTitle method [\#143](https://github.com/skywinder/ActionSheetPicker-3.0/pull/143) ([martinpfannemueller](https://github.com/martinpfannemueller))
- Add TapAction property and fix ActionSheetPickerView when toolbar hiden [\#140](https://github.com/skywinder/ActionSheetPicker-3.0/pull/140) ([qicz](https://github.com/qicz))

## [1.3.13](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.13) (2015-02-09)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.12...1.3.13)

**Fixed bugs:**

- Wrong background color of pickers [\#136](https://github.com/skywinder/ActionSheetPicker-3.0/issues/136)
- Fixed an issue when initial selections applied to picker with different number of rows for different components. [\#113](https://github.com/skywinder/ActionSheetPicker-3.0/pull/113) ([venj](https://github.com/venj))

## [1.3.12](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.12) (2015-02-04)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.11...1.3.12)

**Fixed bugs:**

- Light status bar style [\#119](https://github.com/skywinder/ActionSheetPicker-3.0/issues/119)

**Merged pull requests:**

- Fixes a crash while closing when using the Classy framework for styling [\#128](https://github.com/skywinder/ActionSheetPicker-3.0/pull/128) ([SudeepSidhu](https://github.com/SudeepSidhu))
- .m files should not be included in public header files [\#127](https://github.com/skywinder/ActionSheetPicker-3.0/pull/127) ([ened](https://github.com/ened))

## [1.3.11](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.11) (2015-01-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.10...1.3.11)

## [1.3.10](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.10) (2015-01-09)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.9...1.3.10)

**Implemented enhancements:**

- Should have minimum/maximum date property exposed [\#97](https://github.com/skywinder/ActionSheetPicker-3.0/issues/97)

**Closed issues:**

- No "cancel" button [\#122](https://github.com/skywinder/ActionSheetPicker-3.0/issues/122)
- Swift; Does not conform to protocol [\#120](https://github.com/skywinder/ActionSheetPicker-3.0/issues/120)

**Merged pull requests:**

- add header file to public [\#115](https://github.com/skywinder/ActionSheetPicker-3.0/pull/115) ([skywinder](https://github.com/skywinder))

## [1.3.9](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.9) (2014-12-11)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.8...1.3.9)

**Closed issues:**

- Bad interaction with submodules [\#111](https://github.com/skywinder/ActionSheetPicker-3.0/issues/111)

**Merged pull requests:**

- Fix bad interaction with Git submodules.  Fixes issue \#111. [\#112](https://github.com/skywinder/ActionSheetPicker-3.0/pull/112) ([JimDabell](https://github.com/JimDabell))

## [1.3.8](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.8) (2014-12-10)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.7...1.3.8)

**Fixed bugs:**

- Fixed an issue when more than one ActionSheetCustomPicker is used in a ViewController [\#108](https://github.com/skywinder/ActionSheetPicker-3.0/pull/108) ([venj](https://github.com/venj))

**Closed issues:**

- Redefinition of enumerator 'Selector' [\#109](https://github.com/skywinder/ActionSheetPicker-3.0/issues/109)

**Merged pull requests:**

- Fix for \#109 [\#110](https://github.com/skywinder/ActionSheetPicker-3.0/pull/110) ([michalciolek](https://github.com/michalciolek))

## [1.3.7](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.7) (2014-12-04)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.6...1.3.7)

**Fixed bugs:**

- UIDatePicker does not fire the target-action associated with the UIControlEventValueChanged event the first time [\#104](https://github.com/skywinder/ActionSheetPicker-3.0/issues/104)
- Added workaround for a bug in UIDatePicker in count down mode. [\#105](https://github.com/skywinder/ActionSheetPicker-3.0/pull/105) ([tomaskraina](https://github.com/tomaskraina))

**Merged pull requests:**

- Add a Bitdeli Badge to README [\#107](https://github.com/skywinder/ActionSheetPicker-3.0/pull/107) ([bitdeli-chef](https://github.com/bitdeli-chef))
- Added minimumDate and maximumDate to contructor of ActionSheetDatePicker [\#98](https://github.com/skywinder/ActionSheetPicker-3.0/pull/98) ([emmanuelay](https://github.com/emmanuelay))

## [1.3.6](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.6) (2014-12-02)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.5...1.3.6)

**Fixed bugs:**

- Example projects failed to launch [\#96](https://github.com/skywinder/ActionSheetPicker-3.0/issues/96)

**Closed issues:**

- Travis builds is broken by fix \#96 [\#99](https://github.com/skywinder/ActionSheetPicker-3.0/issues/99)

## [1.3.5](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.5) (2014-11-14)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.4...1.3.5)

**Fixed bugs:**

- StatusBar visibility [\#90](https://github.com/skywinder/ActionSheetPicker-3.0/issues/90)

**Merged pull requests:**

- Update README.md [\#95](https://github.com/skywinder/ActionSheetPicker-3.0/pull/95) ([jeffreyjackson](https://github.com/jeffreyjackson))

## [1.3.4](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.4) (2014-11-12)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.3...1.3.4)

**Merged pull requests:**

- Fix statusBar visibility [\#93](https://github.com/skywinder/ActionSheetPicker-3.0/pull/93) ([krin-san](https://github.com/krin-san))

## [1.3.3](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.3) (2014-11-12)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.2...1.3.3)

**Fixed bugs:**

- Compiler warning due to Unicode char in source [\#92](https://github.com/skywinder/ActionSheetPicker-3.0/issues/92)

## [1.3.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.2) (2014-11-11)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.1...1.3.2)

**Implemented enhancements:**

- Add delegate for custom button pressed [\#33](https://github.com/skywinder/ActionSheetPicker-3.0/issues/33)

**Merged pull requests:**

- Add additional check for UIDatePickerModeCountDownTimer [\#91](https://github.com/skywinder/ActionSheetPicker-3.0/pull/91) ([skywinder](https://github.com/skywinder))
- Count down duration fix [\#89](https://github.com/skywinder/ActionSheetPicker-3.0/pull/89) ([ijameelkhan](https://github.com/ijameelkhan))

## [1.3.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.1) (2014-11-04)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.3.0...1.3.1)

**Merged pull requests:**

- Fix for \#84 and \#63 [\#85](https://github.com/skywinder/ActionSheetPicker-3.0/pull/85) ([skywinder](https://github.com/skywinder))

## [1.3.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.3.0) (2014-11-03)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.2.0...1.3.0)

**Fixed bugs:**

- iPad - Swift  Popover not visible [\#68](https://github.com/skywinder/ActionSheetPicker-3.0/issues/68)

**Merged pull requests:**

- Added callback for custom button being pressed [\#81](https://github.com/skywinder/ActionSheetPicker-3.0/pull/81) ([velga](https://github.com/velga))
- Added support for popover customizations. [\#77](https://github.com/skywinder/ActionSheetPicker-3.0/pull/77) ([openreply](https://github.com/openreply))

## [1.2.0](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.2.0) (2014-10-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.21...1.2.0)

**Merged pull requests:**

- General fixes for \#74 & \#50 [\#76](https://github.com/skywinder/ActionSheetPicker-3.0/pull/76) ([skywinder](https://github.com/skywinder))
- Further support for countdown timer [\#74](https://github.com/skywinder/ActionSheetPicker-3.0/pull/74) ([mgmart](https://github.com/mgmart))

## [1.1.21](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.21) (2014-10-13)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.20...1.1.21)

**Fixed bugs:**

- i used DatePicker in ActionSheetPicket-3.0, but app crashed. [\#65](https://github.com/skywinder/ActionSheetPicker-3.0/issues/65)

**Closed issues:**

- ActionSheetString picker Crash [\#75](https://github.com/skywinder/ActionSheetPicker-3.0/issues/75)

## [1.1.20](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.20) (2014-10-13)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.19...1.1.20)

**Closed issues:**

- ActionSheetDatePicker: set selectedDate in response to custom button press [\#73](https://github.com/skywinder/ActionSheetPicker-3.0/issues/73)
- Using ActionSheetDatePicker as CountDownTimer-Picker [\#72](https://github.com/skywinder/ActionSheetPicker-3.0/issues/72)
- Example fails when clicking "Modal Test": 'Pushing a navigation controller is not supported' [\#70](https://github.com/skywinder/ActionSheetPicker-3.0/issues/70)

## [1.1.19](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.19) (2014-10-07)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.18...1.1.19)

**Fixed bugs:**

- Xcode 6 / Swift incompatibility [\#36](https://github.com/skywinder/ActionSheetPicker-3.0/issues/36)

**Merged pull requests:**

- title text with attributes. [\#64](https://github.com/skywinder/ActionSheetPicker-3.0/pull/64) ([nebiros](https://github.com/nebiros))

## [1.1.18](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.18) (2014-10-03)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.17...1.1.18)

## [1.1.17](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.17) (2014-10-03)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.16...1.1.17)

## [1.1.16](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.16) (2014-10-03)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.15...1.1.16)

## [1.1.15](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.15) (2014-09-29)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.14...1.1.15)

**Implemented enhancements:**

- Method request: hideActionSheetPicker [\#51](https://github.com/skywinder/ActionSheetPicker-3.0/issues/51)

**Fixed bugs:**

- DatePicker callback freezes screen [\#42](https://github.com/skywinder/ActionSheetPicker-3.0/issues/42)

**Merged pull requests:**

- Fix for UIDatePickerModeCountDownTimer callback [\#50](https://github.com/skywinder/ActionSheetPicker-3.0/pull/50) ([jklp](https://github.com/jklp))

## [1.1.14](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.14) (2014-09-28)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.13...1.1.14)

**Merged pull requests:**

- Update SWActionSheet.m [\#60](https://github.com/skywinder/ActionSheetPicker-3.0/pull/60) ([zhongyang](https://github.com/zhongyang))
- add block based API to date picker [\#56](https://github.com/skywinder/ActionSheetPicker-3.0/pull/56) ([mrtj](https://github.com/mrtj))
- update badge [\#46](https://github.com/skywinder/ActionSheetPicker-3.0/pull/46) ([skywinder](https://github.com/skywinder))
- Add badge [\#45](https://github.com/skywinder/ActionSheetPicker-3.0/pull/45) ([skywinder](https://github.com/skywinder))

## [1.1.13](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.13) (2014-09-19)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.12...1.1.13)

**Closed issues:**

- impossible to run in xcode 6 [\#48](https://github.com/skywinder/ActionSheetPicker-3.0/issues/48)

## [1.1.12](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.12) (2014-09-17)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.11...1.1.12)

**Merged pull requests:**

- reformat [\#44](https://github.com/skywinder/ActionSheetPicker-3.0/pull/44) ([skywinder](https://github.com/skywinder))
- unexpected action sheet dismissing in portrait mode only [\#40](https://github.com/skywinder/ActionSheetPicker-3.0/pull/40) ([numen31337](https://github.com/numen31337))
- Support ActionSheet width to full-screen-width in 4.7 inch and 5.5 inch devices [\#38](https://github.com/skywinder/ActionSheetPicker-3.0/pull/38) ([nowsprinting](https://github.com/nowsprinting))

## [1.1.11](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.11) (2014-09-16)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.10...1.1.11)

**Implemented enhancements:**

- Pop over direction [\#28](https://github.com/skywinder/ActionSheetPicker-3.0/issues/28)
- ActionSheetDatePicker needs done/cancel blocks [\#37](https://github.com/skywinder/ActionSheetPicker-3.0/issues/37)

**Fixed bugs:**

- Show from a presented view controller [\#31](https://github.com/skywinder/ActionSheetPicker-3.0/issues/31)
- ActionSheetStringPicker not showing on iphone [\#30](https://github.com/skywinder/ActionSheetPicker-3.0/issues/30)

**Closed issues:**

- ActionSheetPicker needs cancel block to handle hiding [\#39](https://github.com/skywinder/ActionSheetPicker-3.0/issues/39)

**Merged pull requests:**

- Notify cancel on popover dismiss [\#34](https://github.com/skywinder/ActionSheetPicker-3.0/pull/34) ([ynop](https://github.com/ynop))

## [1.1.10](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.10) (2014-09-04)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.9...1.1.10)

**Merged pull requests:**

- Method for presenting overlapping views. [\#32](https://github.com/skywinder/ActionSheetPicker-3.0/pull/32) ([TonSilver](https://github.com/TonSilver))

## [1.1.9](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.9) (2014-09-03)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.8...1.1.9)

**Merged pull requests:**

- Update SWActionSheet.m [\#29](https://github.com/skywinder/ActionSheetPicker-3.0/pull/29) ([TonSilver](https://github.com/TonSilver))

## [1.1.8](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.8) (2014-08-29)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.7...1.1.8)

## [1.1.7](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.7) (2014-08-29)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.6...1.1.7)

## [1.1.6](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.6) (2014-08-27)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.5...1.1.6)

**Closed issues:**

- Still getting warnings [\#16](https://github.com/skywinder/ActionSheetPicker-3.0/issues/16)

**Merged pull requests:**

- fix readme code [\#26](https://github.com/skywinder/ActionSheetPicker-3.0/pull/26) ([abeyuya](https://github.com/abeyuya))

## [1.1.5](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.5) (2014-08-26)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.4...1.1.5)

**Fixed bugs:**

- Toolbar buttons don't appear when Actionsheet is fired from an iPad Form Sheet or Page Sheet [\#22](https://github.com/skywinder/ActionSheetPicker-3.0/issues/22)

## [1.1.4](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.4) (2014-08-26)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.3...1.1.4)

**Fixed bugs:**

- iOS 8 iPad wrong frame size. [\#18](https://github.com/skywinder/ActionSheetPicker-3.0/issues/18)

**Closed issues:**

- iOS8 - iPad popover, wrong size [\#24](https://github.com/skywinder/ActionSheetPicker-3.0/issues/24)

**Merged pull requests:**

- fix iOS8 wrong popover size in iPad [\#25](https://github.com/skywinder/ActionSheetPicker-3.0/pull/25) ([AdrianFlorian](https://github.com/AdrianFlorian))

## [1.1.3](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.3) (2014-08-25)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.2...1.1.3)

**Closed issues:**

- Presented in wrong frame when sender is a navbar bar button item [\#23](https://github.com/skywinder/ActionSheetPicker-3.0/issues/23)

## [1.1.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.2) (2014-08-15)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.1.1...1.1.2)

**Closed issues:**

- Landscape broken in iOS 7 [\#17](https://github.com/skywinder/ActionSheetPicker-3.0/issues/17)
- Invalid context warning in landscape [\#13](https://github.com/skywinder/ActionSheetPicker-3.0/issues/13)

## [1.1.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.1.1) (2014-08-13)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.18...1.1.1)

## [1.0.18](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.18) (2014-08-12)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.17...1.0.18)

## [1.0.17](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.17) (2014-08-12)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.15...1.0.17)

**Closed issues:**

- Issue with iOS 8 beta  [\#9](https://github.com/skywinder/ActionSheetPicker-3.0/issues/9)

## [1.0.15](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.15) (2014-08-11)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.14...1.0.15)

## [1.0.14](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.14) (2014-08-01)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.13...1.0.14)

## [1.0.13](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.13) (2014-07-30)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.12...1.0.13)

**Closed issues:**

- Use with UITableViewCells [\#4](https://github.com/skywinder/ActionSheetPicker-3.0/issues/4)

**Merged pull requests:**

- Minute Interval for ActionDatePicker [\#12](https://github.com/skywinder/ActionSheetPicker-3.0/pull/12) ([Jack-s](https://github.com/Jack-s))

## [1.0.12](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.12) (2014-07-24)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.11...1.0.12)

**Closed issues:**

- i get this warning!'sizeWithFont:' is deprecated: first deprecated in iOS 7.0 - Use -sizeWithAttributes: [\#11](https://github.com/skywinder/ActionSheetPicker-3.0/issues/11)
- configurePickerView for ActionSheetCustomPicker throws exception [\#10](https://github.com/skywinder/ActionSheetPicker-3.0/issues/10)

## [1.0.11](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.11) (2014-07-19)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.10...1.0.11)

## [1.0.10](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.10) (2014-07-14)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.9...1.0.10)

## [1.0.9](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.9) (2014-07-07)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.8...1.0.9)

**Fixed bugs:**

- Crash when using in 5s iOS 7.1 [\#8](https://github.com/skywinder/ActionSheetPicker-3.0/issues/8)
- On Iphone 4 the ActionSheetStringPicker doesn't work Well [\#5](https://github.com/skywinder/ActionSheetPicker-3.0/issues/5)

## [1.0.8](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.8) (2014-06-29)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.7...1.0.8)

**Merged pull requests:**

- added check for iPhone 4, to fix transparent view background problem. [\#6](https://github.com/skywinder/ActionSheetPicker-3.0/pull/6) ([JaseElder](https://github.com/JaseElder))

## [1.0.7](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.7) (2014-06-20)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.6...1.0.7)

## [1.0.6](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.6) (2014-06-11)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.5...1.0.6)

## [1.0.5](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.5) (2014-05-27)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.4...1.0.5)

## [1.0.4](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.4) (2014-05-25)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/0.0.4...1.0.4)

## [0.0.4](https://github.com/skywinder/ActionSheetPicker-3.0/tree/0.0.4) (2014-05-25)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.3...0.0.4)

**Merged pull requests:**

- Convert screenshots over to iOS 7. [\#3](https://github.com/skywinder/ActionSheetPicker-3.0/pull/3) ([markrickert](https://github.com/markrickert))
- Add basic documentation to the readme. [\#2](https://github.com/skywinder/ActionSheetPicker-3.0/pull/2) ([markrickert](https://github.com/markrickert))

## [1.0.3](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.3) (2014-05-21)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.2...1.0.3)

## [1.0.2](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.2) (2014-05-21)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/1.0.1...1.0.2)

**Implemented enhancements:**

- Get tint color for actionsheet buttons from application window [\#1](https://github.com/skywinder/ActionSheetPicker-3.0/pull/1) ([Mau04](https://github.com/Mau04))

## [1.0.1](https://github.com/skywinder/ActionSheetPicker-3.0/tree/1.0.1) (2014-05-19)

[Full Changelog](https://github.com/skywinder/ActionSheetPicker-3.0/compare/d48b701d6014d66a13d398655368a369a79583bb...1.0.1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
