tably
=====

Tably - PhoneGap app for viewing tabulature via Dropbox

> "I'm a concert pianist. That's a pretentious way of saying I'm... unemployed at the moment." <cite>-- An American in Paris<cite>

Since the dawn of time<sup>1</sup> players of music have stored their cache of illegally transcribed and downloaded tabulature on Dropbox and yearned - nay, tearfully longed - to be able to view said tabulature on their smart phone, tablet or similar device, with smarts like automatic scrolling, transposition and stopping the screen from turning off.

**Long no longer.** For Tably is... 

coming. Maybe.


<small><sup>1</sup> dates may be inaccurate</small>


## TODO

- bootstrap it
- iPhone
- iPad
- Dropbox integration
- navigation
- tab viewer
- indexing and search
- tab highlighting (chords)
- prevent idle screen
- scrolling
- transposition (chords only)
- offline caching
- Android
- Windows Phone 8
- Windows 8 Store version?

## Setting up a development environment
1. Install nodejs
2. [Install PhoneGap using npm](http://phonegap.com/install/)
	- actually it might be better to just use Cordova - `npm install -g cordova`
3. Install the [Android SDK](http://developer.android.com/sdk/) and [add the bits to the path](http://docs.phonegap.com/en/edge/guide_platforms_android_index.md.html#Android%20Platform%20Guide)

### What I did to bootstrap the project - or - A Tale Of Two Frameworks

#### PhoneGap
1. Day one.
2. in the project folder, `cordova create tably com.swxben.tably "Tably"`
3. `cd tably`
4. `cordova platform add andoid`
5. that didn't work so I derped around for a while, gave up, watched an episode of Prime Suspect. Helen Mirren is fantastic.
6. Day two. Installed Android API 17 - run `android` and install API 17 from the SDK manager
7. [Error: An error occured during creation of android sub-project. ERROR : executing command 'ant', make sure you have ant installed and added to your path.
8. ok, this is getting crazy
9. [here are some instructions on installing Ant](http://www.nczonline.net/blog/2012/04/12/how-to-install-apache-ant-on-windows/), which you have to do by hand. [Download Ant here](http://ant.apache.org/bindownload.cgi), I guess. Like all good Apache projects you've got to go down 3 links deep and to a totally different domain to find a zip file to download.
10. wait now it wants me to install Java. head asplodes. All I want to do is bootstrap some code. Bugger this I'm trying Sencha.

#### Sencha

So [Sencha](http://www.sencha.com/) is available in a free commercial version and a GPL 3.0 version. The commercial version is available through an email wall, fair enough I guess, so I downloaded that. A local web server is also required, [XAMPP](http://www.apachefriends.org/en/xampp.html) is cool but I just pointed IIS at my `c:\source`.


