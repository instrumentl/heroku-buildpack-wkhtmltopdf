This installs the last version of wkhtmltopdf (0.12.6.2) into a Heroku application. It supports stacks 20 and 22.

Please note that wkhtmltopdf is no longer maintained upstream and you probably shouldn't use it.

This repository is licensed under the ISC license, a copy of which you can find at [LICENSE.txt](LICENSE.txt). It will
download and install wkhtmltox, which is licensed under the GNU Lesser General Public License version 3.0, the details
of which can be found in [its LICENSE file](https://github.com/wkhtmltopdf/wkhtmltopdf/blob/master/LICENSE).

## Usage

Add this buildpack to your Heroku application to install the `wkhtmltopdf` and `wkhtmltoimage` binaries, and the corresponding library `libwkhtmltox`, into your slug:

```bash
$ heroku buildpacks:add https://github.com/instrumentl/heroku-buildpack-wkhtmltopdf.git
```
