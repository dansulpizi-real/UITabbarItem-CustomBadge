# UITabbarItem-CustomBadge

<img src='https://github.com/ratulSharker/UITabbarItem-CustomBadge/blob/ratul_adding_configurable_properties/iTunesArtwork.jpg' 
width="200px" height="200px">
<br/>

There is no public api from [Apple](https://developer.apple.com/). But it's not impossible to cusotmize the 
[UITabbarItem](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UITabBarItem_Class/) badge 
with [UILabel](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UILabel_Class/). I've been inspired by **enryold**'s [repository](https://github.com/enryold/UITabBarItem-CustomBadge).
I think this could be done in a better way, by overriding the `-(void)setBadgeValue:(NSString*)value` & the `-(NSString*)badgeValue`. In this way an existing project doesn't need to 
change the badge value settings related function calls. This is how the whole thing is maintained.

This project is under the MIT Liecense, feel free to use this code base under compilance.

##Installation
Installation of `UITabbarItem+CustomBadge` is easy, just add [UITabbarItem+CustomBadge](https://github.com/ratulSharker/UITabbarItem-CustomBadge/tree/master/Example/UITabbarItem%2BCustomBadge) category in your xcode project. Change the content of this category to meet your requiremnt and you're good to go.

##Demo
<img src='https://github.com/ratulSharker/UITabbarItem-CustomBadge/blob/ratul_adding_configurable_properties/demo/UITabbarItem%2BCustomBadge%2BDemo.gif'>



Feel free to contact me @Sharker.ratul.08@gmail.com