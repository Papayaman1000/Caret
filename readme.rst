Personal Caret Repackaging
=====

Caret is a lightweight-but-powerful programmer's editor running as a Chrome
Packaged App. I want to monkey around with it and truly make it my own; as such, you (yes, you) likely won't have any use for it.

`// Some docs on how to do what I'm doing that I don't feel like deleting----------------------------------------------------`
You can also load Caret from source code, either to hack around on or
to try the absolute bleeding edge. You'll need to have Node and NPM
installed first, then follow these steps:

0. Clone this repo to your local machine
1. Run ``npm install`` to get the development dependencies (Grunt, LESS,
   and some other packages)
2. Start ``grunt``, which will generate the CSS files from the LESS
   source
3. Visit ``chrome://extensions`` and enable Developer Mode.
4. Still on the extensions page, click the button marked "Load unpacked
   extension..." and select the directory containing Caret's
   manifest.json.

If you use Caret and would like to show your appreciation, please
consider donating to the `FSF's Fund to End Software
Patents <https://my.fsf.org/civicrm/contribute/transact?reset=1&id=17>`__.
