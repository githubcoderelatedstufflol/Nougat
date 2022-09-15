# Nougat
A JavaScript library to emulate Android in a browser. <br>
Credits to browserling! <br>
# Installation
On your webserver, copy the following code into your index.html: <br>
<code>
&lt;div id="display">&lt;/div>
&lt;script src="nougat.js"></script>
</code><br>
And download <code>nougat.js</code> from this repository. Once you've downloaded the file, put it in the same directory as your index.html. You're done!
# Usage
The usage is simple.
<code>
nougat.launch('#display', <android version>, true, true);
</code><br>
For example, to launch Android 6.0, you use: <br>
<code>
nougat.launch('#display', '6.0', true, true);
</code><br>
The list of supported Android versions is listed below: <br>
- [x] Android 4.4
- [x] Android 5.0
- [x] Android 5.1
- [x] Android 6.0
- [x] Android 7.0
- [x] Android 7.1<br>

That's all to it, enjoy! <br>
You can see it live on the following sites: <br>
[nougat.glitch.me](https://nougat.glitch.me/)<br>
[android-emulator.w3spaces.com](https://android-emulator.w3spaces.com/)<br>
[android-emulator.mygamesonline.org](http://android-emulator.mygamesonline.org)<br>
