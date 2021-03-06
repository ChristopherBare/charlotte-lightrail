# Charlotte Light Rail

## Branches
* `master`: The production branch, tagged by release.
* `development`: When you fork this project, you should branch off of this branch and work your magic. (Then send us a PR)
* `android`: Working React Native project on Android! Running, but still some work to do. You may want to work off this one as well.
* `v1.0`: First production version on iOS.

## Contributions
We're excited to open source this project. This is by the community, for the community. We're looking for contributors. If you're interested and/or have any questions, please reach out to us at teamlunaclt@gmail.com or tweet us [@teamlunaco](https://twitter.com/teamlunaco).

If you find any dead code or anything that can be improved, please submit a PR (There's definitely some dead code). New features? Submit a PR. And if you want to help with Android, that'd be great. In fact, here's a list. Pick one. Dive in!

## What's Next?
* Make Mapbox Distance Matrix API calls more efficient. (See Issue #4.)
* Add new light rail extension stations and schedules for the March 16, 2018 opening.
* Support Android.
* Consider reintroducing CodePush and analytics (e.g., Firebase).

## Getting Started

### First-time React Native Setup

If this is your first time running a React Native project on this machine, following the "Getting Started" instructions in the React Native docs [here](https://facebook.github.io/react-native/docs/getting-started.html#requirements). No need to do the `react-native init AwesomeProject` part since this project has already been initialized.

### Keys/Secrets

You will need to get your own [Mapbox API Key](https://www.mapbox.com/help/how-access-tokens-work). Place it in **`env.json`** before you start.

### Project Setup

* `git clone https://github.com/brandonfancher/charlotte-lightrail`
* `cd charlotte-lightrail`
* `git fetch`
* `git checkout development`
* `yarn install`
* **A Simulator must be open in order to run the app.** If you're on a Mac and have Xcode installed: `open /Applications/Xcode.app/Contents/Developer/Applications/Simulator.app`
* `yarn start`

**Note:** If you get an error where assets or components are pointing to a `/node_modules` directory, you may need to manually start the packager with `npm start -- --reset-cache`.

### Tests

Currently, only _Components_ in `src/components` have [jest](https://facebook.github.io/jest/) tests.
* Run Tests: `yarn test` or `yarn test:watch`
* Code Coverage: `yarn test:coverage`

## Currently Using

* [React Navigation](https://github.com/react-community/react-navigation)
* [React Native Mapbox GL](https://github.com/mapbox/react-native-mapbox-gl)
* [Styled Components](https://github.com/styled-components/styled-components)

## Acknowledgements

* [@mdwagner](https://github.com/mdwagner): A big thank you for your very good work refactoring and improving this project.