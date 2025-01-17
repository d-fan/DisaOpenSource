# ![](http://i.imgur.com/g0MZFu1.png) Disa's Open Source Repository


Welcome to Disa's open source repository! Disa is a unified messenger currently available for Android devices (more platforms soon to come!). This open source repository aims to provide you everything needed to start developing your own plugins for your favorite instant messaging platforms (or anything that you can really _make_ out of it).

__Please note that the documention currently provided is in a very preliminary state. Over the next few months, significant efforts will be placed on maturing it. If you can't figure it out, raise an issue or check back a month later (in hope for your question(s) answered with newly provided documentation).__

If you are looking for the latest APK to sideload to your device (for whatever reason you don't or can't use the Play Store), you're in the wrong place. Go here: https://github.com/Dynogic/DisaBuilds

# ![](http://i.imgur.com/5PGlzsV.png)

## Understanding Disa

At the very core of Disa is Disa.Framework. Disa.Framework is code that cross-compiles to any platform that runs Mono/.NET. A front-end is then developed for each platform that hooks into the underlying Disa.Framework. For instance, we use Xamarin.Android to provide a front-end for Android (called Disa.Android respectively).

Thus, if done correctly, your plugin will run on any platform that Disa.Framework runs on - "write once, run anywhere".

## Documentation, Roadmap & Contributing

Head over to the [Wiki](//github.com/Disa-im/DisaOpenSource/wiki) where you'll find this information.

## Requesting Features

If there is a feature that you want to be implemented into Disa (e.g: your service has the ability to edit messages after they're sent, and you want that feature in Disa), contact us at opensource@disa.im or raise an issue. Our team will look into the possibility of implementing it.

## Contact

If you have any questions, give us an email at opensource@disa.im.

## License

 (C) Copyright 2015 Disa (http://disa.im).
 
 All rights reserved. This program and the accompanying materials
 are made available under the terms of the GNU Lesser General Public License
 (LGPL) version 2.1 which accompanies this distribution, and is available at
 http://www.gnu.org/licenses/lgpl-2.1.html

 This library is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
 Lesser General Public License for more details.

