# OHANA_API

> Anticloud offline package — upstream: codeforamerica/ohana-api @ `master`.

## What This Project Does

The open source API directory of community social services.

## Upstream README

# Ohana API

[![CircleCI](https://circleci.com/gh/codeforamerica/ohana-api/tree/master.svg?style=svg)](https://circleci.com/gh/codeforamerica/ohana-api/tree/master) [![Maintainability](https://api.codeclimate.com/v1/badges/64c25ee17eae19dd61ed/maintainability)](https://codeclimate.com/github/codeforamerica/ohana-api/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/64c25ee17eae19dd61ed/test_coverage)](https://codeclimate.com/github/codeforamerica/ohana-api/test_coverage)

Ohana API is a Ruby on Rails application that makes it easy for communities to publish and maintain a database of social services, and allows developers to build impactful applications that serve underprivileged residents.

This is the API + Admin Interface portion of the Ohana project, developed by [@monfresh](https://github.com/monfresh), [@spara](https://github.com/spara), and [@anselmbradford](https://github.com/anselmbradford) during their Code for America Fellowship in 2013, in partnership with San Mateo County's Human Services Agency.

Apps built on top of Ohana API include a [web-based search interface](https://github.com/codeforamerica/ohana-web-search) and an [SMS app] that allow anyone to easily find services that are available in a particular community.

[SMS app]: https://github.com/monfresh/ohana-sms

## Stack Overview

* Ruby version 2.7.5
* Rails version 5.2.6
* Postgres
* Testing Frameworks: RSpec, Factory Girl, Capybara

## Local Installation

Follow the instructions in [INSTALL.md][install] to get the app up and running, and to learn how to import your data.

[install]: https://github.com/codeforamerica/ohana-api/blob/master/INSTALL.md

## Demo
You can see a running version of the different parts of the application here:

**Developer portal**: [http://ohana-api-demo.herokuapp.com/](http://ohana-api-demo.herokuapp.com/)
(see [db/seeds.rb][developer_portal_seeds] for two usernames and passwords you can sign in with).

**API**: [http://ohana-api-demo.herokuapp.com/api](http://ohana-api-demo.herokuapp.com/api)

**Admin Interface**: [http://ohana-api-demo.herokuapp.com/admin](http://ohana-api-demo.herokuapp.com/admin)
(see [db/seeds.rb][admin_interface_seeds] for three usernames and passwords you can sign in with).

[developer_portal_seeds]: https://github.com/codeforamerica/ohana-api/blob/master/db/seeds.rb#L10-L23
[admin_interface_seeds]: https://github.com/codeforamerica/ohana-api/blob/master/db/seeds.rb#L25-45

## API documentation
[http://codeforamerica.github.io/ohana-api-docs/](http://codeforamerica.github.io/ohana-api-docs/)

## Client libraries

- Ruby: [Ohanakapa][ohanakapa] (our official wrapper)

We would love to see libraries for other programming languages.
If you've built one, let us know and we'll add it here.

[ohanakapa]: https://github.com/codeforamerica/ohanakapa

## Taxonomy
Out of the box, this project supports the [Open Eligibility](http://openeligibility.org)
taxonomy. If you would like to use your own taxonomy, or add

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
