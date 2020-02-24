# india-pincode-regex

Validate a [Postal Index Number][wiki] for India with a regex. The regexes are available in `regex.txt`. There are 2 regexes. The first validates PINs starting from 1-4, and the second validates the ones starting from 5-8. The reason for the split is to keep the regex size small. Currently they are both at 16K each.

## Source

The source for the data is the ["All India Pincode Directory"](https://data.gov.in/resources/all-india-pincode-directory) dataset on data.gov.in.

## Usage

The `regex.txt` file is 32KB in size, so you can easily use it wherever you want, including browsers.

## License

Licensed under the [MIT License](https://nemo.mit-license.org/). See LICENSE file for details.

[wiki]: https://en.wikipedia.org/wiki/Postal_Index_Number