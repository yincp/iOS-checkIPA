# iOS IPA Validator #

### v1.5 and bellow: by G. Gold gold@apperian.com ###

`checkipa` scans an IPA file and parses its Info.plist (in Payload directory)
and embedded.mobileprovision files. It performs checks of expected key/value
relationships and reports the results.

### v1.6 and upper: by G. Yincp yincp@126.com ###

Forked from https://github.com/apperian/iOS-checkIPA (v1.5). From v1.6 by yincp,
this tool cant output json format content and extract a most suitable icon file
from the ipa.

## Installation ##

put `checkipa` file in your path and make it executable.

## Usage ##

Launch your favorite terminal program and run program, e.g.:

    $ checkipa -i "file name.ipa" -j

For options:

    $ checkipa --help
