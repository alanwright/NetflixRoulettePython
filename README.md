NetflixRoulettePython
=====================

A Python wrapper for the [NetflixRouletteAPI](http://netflixroulette.com/api) - extended from the original by [CodeUSASoftware](http://blog.codeusa.net/). Methods that were extended are mentioned in bold in the Methods section, all other methods were taken from the original source. The original source can be installed via pip: `pip install NetflixRoulette`

## Setup
All you need to do is place the .py and .pyc file in the following directory on your machine:

> path\to\Python27\Lib\site-packages

## Contributing
Feel free to fork and add a pull request to add new methods, or add an issue and I will add new methods. You can also tweet me [@iamalanwright](http://twitter.com/iamalanwright).

### Recompiling
If you decide to make your own changes and want to recompile hte .pyc file, simply open your command prompt or terminal to the directory of the new .py file and run the following commands:

```
$ python
>>> import py_compile
>>> py_compile('NetflixRoulette.py')
```

## Methods
Here is a list of all currently supported methods:
* def get_version()
* get_media_rating(show_title, year=0)
* def get_media_poster(show_title, year=0)
* get_media_type(show_title, year=0)
* get_media_release_year(show_title, year=0)
* get_media_cast(show_title, year=0)
* get_media_category(show_title, year=0)
* get_media_summary(show_title, year=0)
* get_media_director(show_title, year=0)
* get_netflix_id(show_title, year=0)
* get_all_data(show_title, year=0)
* **get_all_data_director(media_director, year=0)**
* **get_all_data_actor(media_actor, year=0)**

**bold** texts designates a method I contributed. 
