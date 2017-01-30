# Dimension

Dimension is a single page and responsive site template. It is a port of [HTML5 UP's Dimension theme](https://html5up.net/uploads/demos/dimension/).

![Dimension Theme screenshot](https://raw.githubusercontent.com/sethmacleod/dimension/master/images/screenshot.png)

## Installation

Run the following commands inside your Hugo site folder:

    $ cd themes
    $ git clone https://github.com/sethmacleod/dimension.git

## Getting Started

After installation, you will need to configure the config.toml file, change pictures, and write your pages.

### The config file

Copy the `config.toml` from the exampleSite folder into your Hugo site's root folder. Change the fields as needed. Add or delete social media by following the examples in the file. You may need to look up the [font-awesome](http://fontawesome.io/) icon names. The icon field should be filled out without the "fa" prefix. The icon field for Twitter should be 'twitter' instead of 'fa-twitter'.

You can change the logo as well with font-awesome icons. The default is set to `fa-diamond`.

### Changing pictures

Create an `img` folder in the static folder of your site -- **not** the theme's static folder. Add pictures to `/static/img` as needed. The background image should be named `bg.jpg`. The default names for the other images are `pic01.jpg`, `pic02.jpg`, and `pic03.jpg`, but you may use your own naming scheme when you edit `index.html`.

### Writing your pages

Since this theme uses modals instead of separate content pages, it is best to simply edit the `index.html` file to edit your site. Copy the `index.html` file to your `layouts` folder before editing. Follow the example pages in the `index.html` file and adjust as needed.

### Contact Form

You will need to use an external service for the contact form since static sites cannot handle forms on their own. One such service is [Formspree](https://formspree.io/). Formspree has a free tier.

## License

This theme is released under the CC BY 3.0 license. For more information, read the [License](https://github.com/sethmacleod/dimension/blob/master/LICENSE.md).
