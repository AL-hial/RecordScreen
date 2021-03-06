# RecordScreen

RecordScreen is a universal iPhone and iPad application that allows you to record your screen, even on non-jailbroken devices.


## Introduction

I wanted to play around with screen recording capabilities, so I created a fresh Xcode project and used [RecordMyScreen](https://github.com/coolstar/RecordMyScreen) as a starting point.

I also took the chance to play around with designs and rethink the interface from scratch. I tried to keep the app as minimal as possible. I'm still learning about design, so if you think you have something better, feel free to make a Pull Request! :)


## Screenshots

* <img alt="Screenshot 1" width="320" height="568" src="http://f.cl.ly/items/080e1V2R1L0Z3U2g0K0E/photo+1.PNG" />&nbsp;&nbsp;&nbsp;<img alt="Screenshot 2" width="320" height="568" src="http://f.cl.ly/items/2H3R1y2j1a13403c1H3S/photo+2.PNG" />
* <img alt="Screenshot 3" width="320" height="568" src="http://f.cl.ly/items/1E460U0g0u41061F3g10/photo+3.PNG" />&nbsp;&nbsp;&nbsp;<img alt="Screenshot 4" width="320" height="568" src="http://f.cl.ly/items/0v023W462m1Q2q3Y1g3U/photo+4.PNG" />


## Why isn't this on the App Store?

This app cannot be submitted to the App Store due to the use of private APIs. Apple prohibits developers from submitting apps that use any API that is not public.


## Getting Started

Run the following commands to get started:

    $ git clone --recursive https://github.com/nicolasgomollon/RecordScreen.git
    $ cd RecordScreen
    $ rake setup


## Technical Specifications

_TIP: Check out the [iOS Support Matrix](https://www.dropbox.com/s/8ex254t1pscshdp/iOS_Support_Matrix_V14_A3.pdf) for help._

1. ARMv7 device (A5 recommended, _may_ work on iPod touch 2G but untested)
2. iOS 5 or higher (iOS 6 recommended, _may_ work on iOS 4)
3. [iOS Developer Account](https://developer.apple.com/devcenter/ios/index.action) **OR** jailbroken device to install
4. Xcode 4.4.1 or higher


## Known Issues

* **The app does not work on the iPad, even though it is universal.** I've only played around with the app on my iPhone, so I haven't looked into it yet.


## Sources

I used the following resources _(no infringement of any kind intended)_:

* Based off of code from [RecordMyScreen](https://github.com/coolstar/RecordMyScreen).
* Camera icon taken from [Paco Xiao](http://twitter.com/pacoxiao) on [Dribbble](http://dribbble.com/shots/746550-Camera-iOS-Icon).
* Uses [MTStatusBarOverlay](https://github.com/myell0w/MTStatusBarOverlay).
* The [Arches](http://subtlepatterns.com/arches/) background texture used throughout the app was taken from [Subtle Patterns](http://subtlepatterns.com/).
* The typeface used for the navigation bar and cell delete button is [Myriad Pro](https://typekit.com/fonts/myriad-pro) by [Adobe](https://typekit.com/foundries/adobe).
* The typeface used for the all-in-one record button is [Gotham](http://www.typography.com/fonts/font_overview.php?productLineID=100008) by [H&FJ](http://www.typography.com/).
* _Unfortunately, I don't think I'm allowed to distribute those, but you can replace them with the typeface(s) of your choice._


## License

RecordScreen is released under the MIT License.



Too bad this app will never have the chance to be published on the App Store! _(Let me know if you do manage to, though!)_
