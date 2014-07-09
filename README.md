# Structuring an iOS Project

This document describes how to organize an iOS project. The directory structure using folders on the filesystem should be mirrored in Xcode with groups.

## Project Structure

```
/<project-name>
	/app				# app delegate
	/shared
		/controllers
		/views	
	/ipad
		...				# same structure as 'shared'
	/iphone
		...				# same structure as 'shared'
	/models
	/resources			# images, videos, etc
	/support			# categories, helpers, defines, main, .plist, .pch files
	/vendor				# 3rd party dependencies not managed by cocoapods
```

Further discussion on organizing resources can be found [here](https://github.com/dkhamsing/ios-asset-names).

# Acknowledgement

Thanks to [Sebastian Rehnby](http://www.sebastianrehnby.com/blog/2013/01/15/structuring-an-ios-project/).


# Contact

- [github.com/dkhamsing](https://github.com/dkhamsing)
- [twitter.com/dkhamsing](https://twitter.com/dkhamsing)
