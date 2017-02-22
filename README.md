# phpextras

This includes the settings for:

* suhosin
* xcache

## Deploy

### Debian Squeeze

Copy the files to `/etc/php5/conf.d/.`

on the server, go to webpage directory and type:

    ln -s  /usr/share/xcache/admin xcachepage

go to `http://domain/xcachepage`

## Testing

    # php -v
    PHP 5.3.3-7+squeeze19 with Suhosin-Patch (cli) (built: Feb 17 2014 10:10:23) 
    Copyright (c) 1997-2009 The PHP Group
    Zend Engine v2.3.0, Copyright (c) 1998-2010 Zend Technologies
    with XCache v1.3.0, Copyright (c) 2005-2009, by mOo
    with Suhosin v0.9.32.1, Copyright (c) 2007-2010, by SektionEins GmbH
