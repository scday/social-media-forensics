# Social Media Forensics

This project aims to make available tools and software for forensics over social media.

## Datasets

TODO

## Installation

TODO: Describe the installation process

## Usage

### Microblog Authorship Attribution

Code related to tackle the problem of authorship attribution over micro blog social media like Twitter.

The code is organized into these three directories:

* `dataset_pre_processing`: code that pre-processes the data before to trigger the model learning. Examples of pre-processing are language filtering, data tagging and n-grams generation.
* `classification`: code to learn a model and run a classifier.
* `experiment_scripts`: examples of scripts to run the code in the above directories.

Each script (except the ones presented in `experiment_scripts` directory) has a `-h/--help` command-line option that presents an usage explanation describing each option meaning.

#### Dataset Pre-Processing

The `dataset_pre_processing` directory contains code to act over the dataset in order to prepare the data to be run by the code in `classifier` directory. All the code are optional but `ngrams_generator.py`.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

TODO: Write license
