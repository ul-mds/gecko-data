This repository contains example data for use with [Gecko](https://github.com/ul-mds/gecko) &mdash; a Python library for generation and mutation of realistic data at scale.
All data present in this repository is collected from public data sources.
Feel free to use it to test Gecko's capabilities.

# Usage

Clone this repository to an easy-to-find location.

```bash
git clone https://github.com/ul-mds/gecko-data.git
```

You can now use the data in this repository in your Gecko scripts.

# Structure

Subdirectories are locales which identify the language and country that the data contained within pertains to.
Currently, there exists data for the following locales:

- [English (United States)](./en_US/)
- [German (Germany)](./de_DE/)

There is also a [directory called "common"](./common/) which contains data independent of language and country.

Each subdirectory contains a README file which lists the sources and additional pre-processing steps to make the data easier to work with.
If you intend to publish data generated with data from this repository, please take care to cite the correct sources from these README files.

# License

Gecko is released under the MIT License.
