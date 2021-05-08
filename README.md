# Naver Search

A firefox extension which adds www.naver.com as a search engine.

## Download

[firefox add-ons](https://addons.mozilla.org/ko/firefox/addon/naver-search/)

## Usage

![naver-search](./img/naver-search.gif)

## Build From source

### Prerequisite

- [nvm](https://github.com/nvm-sh/nvm#install--update-script)

### Build

- Nvm setup
  - `nvm install` (if not installed)
  - `nvm use`
- Install dependencies
  - `npm install`
- Run
  - `npm run start` (`npm run start -- --help` for help)
- Bundle
  - `npm run build` (`npm run build -- --help` for help)
- Install Locally
  - https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/
  - Load `dist/naver_search-x.x.x.zip` file