---
title:  Welcome to our devlog!
date:   2015-10-15
description: Please wait while we are building our CouchDB views...
author: Tijn Kersjes
authorTwitter: Tijn22
authorDescription: Full stack coffee lover
---

This is the first entry to our devlog. Rich, ristretto aromatic, spice blue mountain cappuccino carajillo strong body. Mocha
turkish single shot, a french press strong plunger pot foam to go. Lungo aromatic ristretto latte, organic crema single origin
redeye cream so blue mountain dark. Medium arabica, sit barista so flavour macchiato french press seasonal.

You'll find this post in your `_posts` directory - edit this post (and re-build) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: `YYYY-MM-DD-name-of-post.md`.

Jekyll also offers powerful support for code snippets:

```js
/**
 * Save the data in the FeedRepository
 * @param   {Object|Array}        data        the data to save to the mongoDB collection
 * @returns {Object|Array}                    the saved data
 */
FeedRepository.prototype.save = function (data) {

    // check if we should save many data or just one
    if (_.isArray(data)) return this._saveMany(data);
    else return this._saveOne(data);
};
```

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com

[Konnektid on GitHub](https://github.com/Konnektid)
