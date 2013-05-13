This was an attempt topull the [multi-platform Cocos2d-x Javascript template](https://github.com/cocos2d/cocos2d-x/tree/master/template/multi-platform-js) out and set it up in a way that it could easily bootstrap a new project.  It has since morphed into my starter project for multiplatform [Cocos2d-x](http://www.cocos2d-x.org/) projects with Javascript and [Cocosbuilder](http://cocosbuilder.com/).  This may or may not be what you are looking for.  If it is, try it out and let me know what is missing or still needs work.

**This is a work in progress and is still open to changes in project structure.**

## Getting Started

		git clone https://github.com/gdagley/cocos2d-x-multi-platform-js my_new_project_name
		cd my_new_project_name
		git submodule update --init --recursive
		# change references to HelloJavascript
		gem install bundler
		bundle install
		./rename project

### iOS

Open the Xcode project file in the proj.ios folder.

### Android

Follow the instructions in the [proj.android/README](https://github.com/gdagley/cocos2d-x-multi-platform-js/tree/master/proj.android).

### Web/HTML

		adsf -r published/HTML

## To do:

* Make it easy to make sure latest shared Javascript source and assets are available in each platform build.
* Make it easy to test the Javascript code.
* Provide examples of custom JS bindings
* Anything else?

## Known Issues:

* Current cocos2d-x is [cocos2d-2.1rc0-x-2.1.2](https://github.com/cocos2d/cocos2d-x/tree/cocos2d-2.1rc0-x-2.1.2)
* proj.win32 has been removed until it can be fixed and tested.
