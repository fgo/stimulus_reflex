<p align="center">
  <img src="assets/stimulus-reflex-logo-with-copy.svg" width="360" />
  <h1 align="center">Welcome to StimulusReflex 👋</h1>
  <p align="center">
    <img src="https://img.shields.io/gem/v/stimulus_reflex.svg?color=red" />
    <img src="https://img.shields.io/npm/v/stimulus_reflex.svg?color=blue" />
    <a href="https://www.npmjs.com/package/stimulus_reflex">
      <img alt="downloads" src="https://img.shields.io/npm/dm/stimulus_reflex.svg?color=blue" target="_blank" />
    </a>
    <a href="https://github.com/hopsoft/stimulus_reflex/blob/master/LICENSE">
      <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-brightgreen.svg" target="_blank" />
    </a>
    <a href="http://blog.codinghorror.com/the-best-code-is-no-code-at-all/" target="_blank">
      <img alt="Lines of Code" src="https://img.shields.io/badge/lines_of_code-1227-brightgreen.svg?style=flat" />
    </a>
    <a href="https://docs.stimulusreflex.com/" target="_blank">
      <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
    </a>
    <br />
    <a href="#badge">
      <img alt="semantic-release" src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg">
    </a>
    <a href="https://github.com/testdouble/standard" target="_blank">
      <img alt="Ruby Code Style" src="https://img.shields.io/badge/Ruby_Code_Style-standard-brightgreen.svg" />
    </a>
    <a href="https://github.com/sheerun/prettier-standard" target="_blank">
      <img alt="JavaScript Code Style" src="https://img.shields.io/badge/JavaScript_Code_Style-prettier_standard-ff69b4.svg" />
    </a>
    <br />
    <a href="https://www.codacy.com/manual/hopsoft/stimulus_reflex/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=hopsoft/stimulus_reflex&amp;utm_campaign=Badge_Grade" target="_blank">
      <img alt="Code Quality" src="https://app.codacy.com/project/badge/Grade/d1d72a7060f5467b8696884351cf477f"/>
    </a>
    <a href="https://codeclimate.com/github/hopsoft/stimulus_reflex/maintainability" target="_blank">
      <img alt="Maintainability" src="https://api.codeclimate.com/v1/badges/2b24fdbd1ae37a24bedb/maintainability" />
    </a>
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/hopsoft/stimulus_reflex/workflows/Prettier-Standard/badge.svg">
      <img src="https://github.com/hopsoft/stimulus_reflex/workflows/Prettier-Standard/badge.svg" alt="Prettier-Standard" style="max-width:100%;">
    </a>
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/hopsoft/stimulus_reflex/workflows/StandardRB/badge.svg">
      <img src="https://github.com/hopsoft/stimulus_reflex/workflows/StandardRB/badge.svg" alt="StandardRB" style="max-width:100%;">
    </a>
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/hopsoft/stimulus_reflex/workflows/Tests/badge.svg">
      <img src="https://github.com/hopsoft/stimulus_reflex/workflows/Tests/badge.svg" alt="Tests">
    </a>
  </p>
</p>
<br />


### 🎉 **An exciting new way to build modern, reactive, real-time apps with Ruby on Rails.**

StimulusReflex eliminates the complexity imposed by full-stack frontend frameworks.
And, it's fast.

It works seamlessly with the Rails tooling you already know and love.

- Server-rendered HTML, delivered in miliseconds over the wire via Websockets
- ERB templates and partials, with first-class [ViewComponent](https://github.com/github/view_component) support
- [Russian doll caching](https://edgeguides.rubyonrails.org/caching_with_rails.html#russian-doll-caching) and [ActiveJob](https://guides.rubyonrails.org/active_job_basics.html)
- [StimulusJS](https://stimulusjs.org/) and [Turbolinks](https://www.youtube.com/watch?v=SWEts0rlezA)
- Built with [CableReady](https://www.youtube.com/watch?v=dPzv2qsj5L8), our secret power-move

**Our goal is to help small teams do big things with familiar tools.**

This project strives to live up to the vision outlined in [The Rails Doctrine](https://rubyonrails.org/doctrine/).

## 📚 Docs

- [StimulusReflex Documentation](https://docs.stimulusreflex.com)
- [CableReady Documentation](https://cableready.stimulusreflex.com)

## ✨ Demos

- [StimulusReflex Expo](http://expo.stimulusreflex.com) - part showcase, part learning tool
- [Build a Twitter Clone in 10 Minutes](https://youtu.be/F5hA79vKE_E) (video)
- [BoxDrop](https://dropbox-clone-rails.herokuapp.com/) - a Dropbox-inspired [concept demo](https://github.com/marcoroth/boxdrop/)

## 👩‍👩‍👧 Discord Community

Please join over 600 of us on [Discord](https://discord.gg/XveN625) for support getting started, as well as active discussions around Rails, StimulusJS and CableReady.

![](https://img.shields.io/discord/629472241427415060)

Stop by #newcomers and introduce yourselves!

## 💙 Support

Your best bet is to ask for help on Discord before filing an issue on Github. We are happy to help, and we ask people to come with all relevant code to look at. A git repo is preferred, but Gists or posts on [Discourse](https://stimulus-reflex.discourse.group) are fine, too.

Please note that we are not actively providing support on Stack Overflow. If you post there, we likely won't see it.

## 🚀 Install

CLI and manual setup procedures are fully detailed in the [official docs](https://docs.stimulusreflex.com/setup).

## 🙏 Contributing

### Code of Conduct

Everyone interacting with the StimulusReflex project’s codebases, issue trackers, chat rooms and forum is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

### Coding Standards

This project uses [Standard](https://github.com/testdouble/standard) for Ruby code
and [Prettier-Standard](https://github.com/sheerun/prettier-standard) for JavaScript code to minimize bike shedding related to source formatting.

Please run `./bin/standardize` prior to submitting pull requests.

View the [wiki](https://github.com/hopsoft/stimulus_reflex/wiki/Editor-Configuration) to see recommendations for configuring your editor to work best with the project.

## 📦 Releasing

1. Bump version number at `lib/stimulus_reflex/version.rb`
1. Run `rake build`
1. Run `rake release`
1. Change directories `cd ./javascript`
1. Run `yarn publish` - NOTE: this will throw a fatal error because the tag already exists but the package will still publish


## 📝 License

StimulusReflex is released under the [MIT License](LICENSE.txt).

---

_Originally inspired by [Phoenix LiveView](https://youtu.be/Z2DU0qLfPIY?t=670)._ 🙌
