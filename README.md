# brogue
My fixes for Brogue on macOS

I was experiencing some random crashes on macOS. I suspect the crashes were due to event handling off the main thread, though I don't have any tests to prove that. This repository updates Brogue to Swift 5, puts all event handling on the main thread, and also corrects an `NSDateFormatter` deprecation warning.
