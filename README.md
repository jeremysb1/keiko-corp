# Website Optimization

The purpose of this project is to analyze the website performance using PageSpeed Insights by Google and fix any performance issues.

1. enter website url in PageSpeed Insights at https://developers.google.com/speed/pagespeed/insights/
2. analyze results

## initial results

Note overall score of 67

![PageSpeed Score !](https://github.com/jeremysb1/keiko-corp/blob/master/Initial%20PageSpeed%20results.png)

## actions taken

1.  I moved the script tags from the head section to the bottom of the body section in the index.html file.
2.  I evaluated which files were not minimized, and which ones could be eliminated.
3.  Removed 3rd party CSS packages which didn't add much to the UX and minified the main CSS file.

## remaining actions to improve performance

1.  remove jquery and replace with native javascript
2.  optimize images and assets above the fold
