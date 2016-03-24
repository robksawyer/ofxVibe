ofxVibe
=====================================

This OpenFrameworks addon implements the [ViBe](https://en.wikipedia.org/wiki/ViBe) background subtraction algorithm.
My code was heavily inspired by [Sergei Belousov](https://github.com/BelBES), so I'd like to credit [his work](https://github.com/BelBES/VIBE).


License
-------
ViBe is patented: in order to use it in any commercial content you should [ask for licensing](http://www.vibeinmotion.com/Licensing.aspx).

I have no relationship with the patent holders and the code presented here is just an experiment to better understand the algorithm and to evaluate its performance.

Installation
------------
- Copy to your openFrameworks/addons folder.
- Ensure that you've properly setup your [ofxCv](https://github.com/kylemcdonald/ofxCv) addon. It has to include `opencv` and you must ensure that `../../../addons/ofxOpenCv/libs/opencv/include/` (See Project Setup on ofxCv.) is in your header paths for both target and project. I also changed `Enable Modules (C and Objective-C)` under build settings for both as well.

Dependencies
------------
- ofxCV

Compatibility
------------
Open Frameworks 0.9.x

Known issues
------------
none

Version history
------------
0.1 – Updated the example for OF 0.9.3
