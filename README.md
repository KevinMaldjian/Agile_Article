# Vsouza's Curated List of iOS Libraries


When developing an iOS application, one might find it very hard to create
each and every part of the app from scratch. Thankfully there are many libraries
that can help a developer implement new features in a much more efficient manner.
@vsouza has curated a list of hundreds of these libraries for Swift and
Objective-c. I personally have used dozens of libraries from this list and I
think it is a vital asset to anyone looking to code their own apps with a very
small team.


The list can be found [here](https://github.com/vsouza/awesome-ios)


### Installing the libraries

What is very convenient about most of the iOS libraries is that they can be
installed with an application level dependency manager such as [Carthage](https://github.com/Carthage/Carthage) or
[Cocoapods](https://cocoapods.org/). They are both very easy to use, I prefer
Cocoapods which can be installed by typing


```
$ sudo gem install cocoapods
```

In the terminal and then

```
pod install
```
on the directory you wish to install the libraries.

### Mahataz Khandaker
One library that I think would be very useful is the Venmo API. One can integrate Venmo payments and requests in his/her application by adding the following line to the Podfile (if CocoaPods is used):
```
pod 'Venmo-iOS-SDK', '~>1.3'
```
It's also an open-source library so contributions are welcomed.