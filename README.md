# Tabler vCIJ

This is my modified version of Tabler for CIJ.

## Installation

- [Install Ruby+Devkit 2.7.6](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.7.6-1/rubyinstaller-devkit-2.7.6-1-x64.exe).  (Including MYS2 etc; all the options)
- [Read guide](https://jekyllrb.com/docs/installation/windows/) to get Jekyll up and running without problems.
- ```shell
  ridk install
  # Open new command prompt
  gem install jekyll bundler
  # Make sure it installed properly
  ```

## Build locally

You need to have `pnpm` and `bundler` installed.

1. From the root directory, run installation in the command line:
  - `pnpm install` 
  - `bundler install` 
2. Then execute `pnpm run start-plugins` to start up the application stack.
3. Open [http://localhost:3000](http://localhost:3000) in your browser ([http://localhost:3001](http://localhost:3001) to configure the Web server).
4. Any change in the `/src` directory will build the application and refresh the page.
5. Run `pnpm run build` to do an actual build that affects the dist directory

## License

See the [LICENSE](https://github.com/tabler/tabler/blob/master/LICENSE) file.