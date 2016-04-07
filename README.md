Fuse CocoaPods
==============

Module to use [CocoaPods](https://cocoapods.org/) in [Fuse](http://www.fusetools.com/).

## Installation

Using [fusepm](https://github.com/bolav/fusepm)

    $ fusepm install https://github.com/bolav/fuse-cocoapods


## Usage:

Create a .uxl file that is included in your .unoproj. For instance `CocoaPods.uxl`.

    <Package>
        <Extensions Backend="CPlusPlus" Condition="iOS">
            <ProcessFile Name="Podfile" />
        </Extensions>
    </Package>

And then create the Podfile you want.