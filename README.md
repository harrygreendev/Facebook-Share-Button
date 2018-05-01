# Facebook Share Button
## Overview
Javascript code that enable users to share a page in facebook.
The script uses current page url and its meta title to share it in facebook. Facebook will use the User's account and will require the user to be logged in.
It's an old implementation that doesn't require facebook sdk and it was first used in [roulettepractice.co.uk](http://www.roulettepractice.co.uk/) to let users share their favorite roulette game.

## Usage
Here is an example on how to use the code in a link:
'''html
<a rel="nofollow" target="_blank" href="http://www.facebook.com/" onclick="window.open('http://www.facebook.com/sharer.php?u='+encodeURIComponent(location.href)+'&t='+encodeURIComponent(document.title));return false;" class="facebook">Facebook</a>
'''
