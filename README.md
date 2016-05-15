# android-maps-anchor-bug

Version 9.0.83 of Google Play services breaks icon anchor in Google Maps SDK for Android.
The result is that icons now align differently than in previous versions,
making apps look broken.

See screenshots for examples where the emulator with Google Play services 8.4.89
works the way it's always been, and the ones from the phone with 9.0.83 has
a different anchor point, and it's impossible to change it.


See also: https://code.google.com/p/gmaps-api-issues/issues/detail?id=9768
