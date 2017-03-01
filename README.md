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

Create an `img` folder in the static folder of your site -- **not** the theme's static folder. Add pictures to `/static/img` as needed. If you want to change the background image, the replacement image should be named `bg.jpg`.

### Writing your pages

To create a new page, run the following command inside your Hugo sites:

    $ hugo new your-page.md

Change `your-page` to what you want to name the file. There are three variables that you can change: `title`, `weight`, and `draft`. Weight is set to 0 by default, so be sure to change it.

You can also copy the pages from the exampleSite folder and modify those pages.

### Contact Form

You will need to use an external service for the contact form since static sites cannot handle forms on their own. One such service is [Formspree](https://formspree.io/). Formspree has a free tier. Check out the `formspree.md` page in the exampleSite folder for a template.

## License

This theme is released under the CC BY 3.0 license. For more information, read the [License](https://github.com/sethmacleod/dimension/blob/master/LICENSE.md).
