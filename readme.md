# learn.openspacedata.org

## Contributing

If you're comfortable with web development:

### Requirements

Installing Jekyll should be straight-forward if all requirements are met. Before you start, make sure your system has the following:

- GNU/Linux, Unix, or macOS
- Ruby version 2.0 or above, including all development headers
- RubyGems
- GCC and Make (in case your system doesn’t have them installed, which you can check by running gcc -v and make -v in your system’s command line interface)

### Install with RubyGems

The best way to install Jekyll is via RubyGems. At the terminal prompt, simply run the following command to install Jekyll:

`$ gem install jekyll`

All of Jekyll’s gem dependencies are automatically installed by the above command, so you won’t have to worry about them at all.

### Usage

Jekyll comes with a built-in development server that will allow you to preview what the generated site will look like in your browser locally.

You can run this commands inside the folder:

`$ jekyll serve`

### Directory structure

This is the basic directory structure which looks like this:

```
learn.openspacedata.org/
├── basics/ # The basics guide.
├───────── glossary/index.md # The sections for the basic guide seems like this.
├── for-journalists/ # This is the 'EO for journalists' directory.
├───────── rights-and-licenses/index.md # The sections for this guide seems like this.
├── for-humanitarian-actions/ # This is the 'EO for humanitarian actions' directory for new guides.
├───────── remote-sensing-for-disaster-response/index.md # The sections for this guide seems like this.
├── example-guide/ # This is the dummy directory for new guides. Copy it to start a new guide
├───────── example-guide/index.md # The sections for the example guide seems like this
├── doks-theme/ # Theme directory. Here's defined all styles and the design of the site.
├── _config.yml # Stores Jekyll configuration data.
├── .gitignore # Git related file which specifies intentionally untracked files to ignore.
├── .htaccess # Configuration file for use on web servers running the Apache Web Server software.
├── 404.md # Error 404 layout markdown template.
├── favicon.ico # Favicon icon.
└── index.md # Homepage layout
```

### Publish

Fork this project and submit a PR.

## License

The contents of this guide, is all licenced under the [Creative Commons Attribution Share Alike 4.0](https://choosealicense.com/licenses/cc-by-sa-4.0/).