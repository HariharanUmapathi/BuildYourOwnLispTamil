Build your own Lisp
===================

http://buildyourownlisp.com

Tamil translation
-----------------

The tamil translation are available under **org** folder

### Contributing - Tamil

If you find any grammatical issues, please report it using Github Issues. Or, if
some sentence or paragraph is difficult to understand, feel free to open an
issue with the following title format: `[page number][type] Descriptive Title`.

For example: `[pg.9][grammar] Incorrect verb usage`.

`type` can be one of the following:

- `Typo`: indicates typing mistake.
- `Grammar`: indicates incorrect grammar usage.
- `Style`: indicates a style improvement.
- `Content`: indicates problems with the content.

This idea is taken from https://github.com/ThangaAyyanar/os01_tamil/blob/master/README.md#contributing, this open source book


About
-----

This is the HTML and website code for the book of the above title.

Corrections / Edits / Contributions Welcome

`contact@theorangeduck.com`

Book contents licensed under Creative Commons Attribution-NonCommercial-ShareAlike 3.0

http://creativecommons.org/licenses/by-nc-sa/3.0/

Source code licensed under BSD3

https://opensource.org/license/bsd-3-clause/


Running
-------

You can't just browse the raw HTML files of the site. The links wont work, and it wont have a proper header or footer. If you want to run this website locally, you should install Flask and run the website as follows.

```
pip install Flask cachelib
python lispy.py
```

You can specify port via `$PORT`.

```
env PORT=5000 python lispy.py
```

This will serve the site locally at `http://127.0.0.1:5000/`. You can browse it from there.
