# BooruToolkit
#### modular local image board library organization framework written in Bash
#### version 2.3

[Forum thread on e621](https://e621.net/forum/show/233498)

## Features
* Download metadata from imageboards like e621 (URL can be changed to e926.net to avoid filters)
* Tag files using softlinking on Windows and Linux (and possibly MacOS)
* Tag files using TMSU
* Upload local library to e621 favorites and/or upvoted list
* Download new images from specified queries
* Infinite expandability

## Dependencies
* libxml2-utils (to work with XML APIs)
* curl
* recode
* sed

## Installation

`$ git clone https://github.com/0x7FF/BooruToolkit.git`

`$ bash BooruToolkit/BooruToolkit.sh`

Make sure you leave the main script in its folder.

## Usage

Run the script and follow on-screen instructions. To skip the menu and use the most recent menu selection use argument `--update`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Added some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## Known bugs

- [ ] Recursive mode is not supported on Windows
- [ ] Update mode is not tested yet
- [ ] DLU will only work with simple queries (without special characters like `:` `+` etc.)

## License

BooruToolkit (TagOrganizer) uses MIT license, for more information please consult LICENSE.
