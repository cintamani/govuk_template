The GOV.UK Design System launched on 22 June 2018
===============

GOV.UK Template has now been replaced by the GOV.UK Design System. Template will remain available in case you are currently using it, but is no longer maintained. The Government Digital Service will only carry out major bug fixes and security patches.

The GOV.UK Design System will be updated to ensure the things it contains meet level AA of WCAG 2.1, but Template will not. [Read more about accessibility of the GOV.UK Design System](https://design-system.service.gov.uk/accessibility/).

# GOV.UK Template

This provides a template containing the GOV.UK header and footer, and associated assets. It provides a consistent GOV.UK brand experience across `www.gov.uk` and all services running under the `service.gov.uk` domain.

The template is built from [`source`](source/) files, and multiple packages are generated to support different languages and frameworks.

Packages are available for [RubyGems](https://rubygems.org/gems/govuk_template), NPM ([mustache](https://npmjs.org/package/govuk_template_mustache), [ejs](https://npmjs.org/package/govuk_template_ejs),  [jinja](https://npmjs.org/package/govuk_template_jinja)), and other [templating languages](docs/packaging.md).


## Previewing the template

You can [view a collection of auto-generated examples](https://alphagov.github.io/govuk_template/) of the current govuk_template release, which show how you can use the template.

## Requirements

The Ruby language (1.9.3+), the build tool [Rake](https://github.com/ruby/rake) & the dependancy management tool [Bundler](https://bundler.io/)

## Detailed Docs

* [Development](docs/development.md)
* [Packaging](docs/packaging.md)
* [Publishing](docs/publishing.md)

## Usage

* [Using with Rails](docs/using-with-rails.md)
* [GOV.UK template blocks and their default values (how to customise the template)](docs/template-blocks.md)
* [Setting a Skip link](docs/usage.md#skip-link)
* [Propositional title and navigation](docs/usage.md#propositional-title-and-navigation)

## Contributing

Please follow the [contribution guidelines](https://github.com/alphagov/govuk_template/blob/master/CONTRIBUTING.md).

This is versioned following [Semantic Versioning](http://semver.org).
