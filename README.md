
Staging [![Build Status](https://travis-ci.org/flexion/hud-disaster-data.svg?branch=master)](https://travis-ci.org/flexion/hud-disaster-data)

# HUD Disaster Data Pilot

A pilot of a website that collects and displays disaster data for use by Community Development Block Grant-Disaster Recovery (CDBG-DR) grantees.

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for additional information.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

## Setup
This project includes a [.travis.yml](.travis.yml) file that will facilitate the building, testing, and deploying of the application, following this structure.

|Repo                         | Branch updated     | Build deployed to                      |
|-----------------------------|--------------------|----------------------------------------|
|flexion/hud-disaster-data    | sprint-*           | cloud.gov hud-disaster-data dev        |
|flexion/hud-disaster-data    | master             | cloud.gov hud-disaster-data staging    |
|18F/hud-disaster-data        | master             | cloud.gov hud-disaster-data prod       |

#### Initiation of TravisCI
To include a repo into TravisCI, you must be an admin of that repo.
- Go to [TravisCI](http://travis-ci.com)
- Click **Sign in with GitHub** and sign in
 - *For additional information, see [these directions](https://docs.travis-ci.com/user/getting-started/)*
- Once you’re signed in, and Travis has synchronized your repositories from GitHub, go to your profile page and enable Travis CI for the repository you want to build
  - We already have the [.travis.yml](.travis.yml) in your project, so the first update to the branch will trigger the build and deploy.
- Check the build status page to see if your build passes or fails
