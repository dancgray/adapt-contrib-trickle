adapt-contrib-trickle
=====================

An Adapt core contributed extension that provides vertical locking

Installation
------------

First, be sure to install the [Adapt Command Line Interface](https://github.com/adaptlearning/adapt-cli), then from the command line run:-

        adapt install adapt-contrib-trickle

Usage
-----
To setup locking, add the ``_trickle`` attribute to an article you wish to lock:

```
"_trickle": {
    "_isEnabled":true,
    "button": "Continue to next question?"
}
```

Setting ``_trickle`` on an article will apply trickle to all blocks underneath the article.

When the article/block is complete, a button will appear containing the text you specify in the ``continue`` attribute.
Clicking this button will show and scroll to the next article or block.
