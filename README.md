# Installation

In a mac, open the `Terminal` app and paste the following commands one by one (without the comments):

```sh
# Clone repository
git clone https://github.com/aerialtools/aerialtools.github.io.git
# Enter repository
cd aerialtools.github.io
# Install brew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
# Install node. Latest tested version: v13.8.0 
brew install node
# Install required packages
npm install
```

After that, you can use `gulp` to build the website. The most used commands are:
- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made