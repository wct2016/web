# WordCamp Tokyo 2016 Theme Development

vccw + gulp + Foundation

## Requires

- Virtual Box: v5.0.x
- Vagrant: v1.8.x
- Node.js: Tested on v5.8.0
- npm: Tested on v3.8.1

## Setup

1. Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads).
1. Install [Vagtant](https://www.vagrantup.com/downloads.html).
1. Setup WordPress environment. Recommend [vccw](http://vccw.cc).
1. Clone this repository in your WordPress `themes/` directory.

        $ git clone git@github.com:wct2016/wct2016.git wct2016

1. Start vccw.

        $ cd wct2016; vagrant up

1. Install Node.js and npm. Recommend using [Homebrew](http://brew.sh/).
1. Change the directory to `themes/wct2016/`.

        $ cd path/to/themes/wct2016/

1. Install some dependencies.

        $ npm install

1. Run gulp.

        $ npm run gulp


## Third Party Recourses

### Foudnation
```
src/scss/core/foundation/
src/scss/core/_settings.scss
src/scss/core/_global.scss
src/scss/core/_foundation.scss
```

- License: MIT
- Source: http://foundation.zurb.com/

## License
GNU GENERAL PUBLIC LICENSE Version 2
