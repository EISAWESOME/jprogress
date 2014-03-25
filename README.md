jprogress
=========

JPROGRESS - Shell Script for Batch Converting Baseline JPG Files to Progressive

*

Progressive JPG files are awesome, because "perceived speed is more important than actual speed" on the web (read more [here](http://calendar.perfplanet.com/2012/progressive-jpegs-a-new-best-practice)). Baseline images load one line at a time, while progressive JPG files load an immediate low-res version, then scan again until they're full-resolution. 

This seems to have new relevancy in the era of increasing pixel densities on displays. Paired with a tool like Retina.js, this gives you a complete fade-in from to high-resolution with decent user experience even on a low-speed connection.

Unfortunately, browser support for this OLD technology (progressive JPG files go back to dial-up Internet days) is currently spotty. But if you want to embrace the back-to-the-future Internet future today, `jprogress` is here to help. 

Most JPG files on the web are in baseline format (and probably, most of yours are too) simply because that's the default "export for web" setting in Photoshop. So to bulk convert, just run `jprogress` in your directory and all images will be converted (it's never a bad idea to save a copy of the baseline ones, just in case).




