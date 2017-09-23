### Pico-er theme for Pico CMS

Needed plugins:

* [modified Pico-Tags](https://github.com/lorraul/Pico-Tags)

### Install

Clone the repository to `themes` directory.

### Meta options:

* `Menu` Option to insert page link to menu sections: `Menu:nav` or `Menu: footer`.

* `Image`: Cloudinary public id of an image. Will be included in OG tags, post listing pages and post pages.



### config.php:

Set default image preview used in og tags if meta image is not present
`$config['default_image_url'] = 'http://via.placeholder.com/600x400';`

Set urls for social network pages:
```
$config['facebook'] = 'https://www.facebook.com/';
$config['tumblr'] = 'https://www.tumblr.com/';
$config['googleplus'] = 'https://www.google.com/';
$config['twitter'] = 'https://www.twitter.com/';
$config['instagram'] = 'https://www.instagram.com/';
$config['pinterest'] = 'https://www.pinterest.com/';
```

Set cloudinary account name for post images:
`$config['cloudinary'] = 'dq9ypo3k5';`