#ruby-build-railsexpress

ruby-build-railsexpress is an rbenv plugin that provides an rbenv install command to compile and install Ruby with memory profiling and optimization patches from [Rails Express](https://github.com/skaes/rvm-patchsets) patchset.

## Installation

### Installing as an rbenv plugin

Clone the repository to rbenv plugins directory.

    git clone https://github.com/adymo/ruby-build-railsexpress.git ~/.rbenv/plugins/ruby-build-railsexpress

Now `rbenv install -l` command should see -railsexpress Ruby versions.

To update ruby-build-railsexpress, go into the `~/.rbenv/plugins/ruby-build-railsexpress` directory and run `git pull` to download the latest changes.

### Installing with Homebrew (for OS X users)

Still in development. Coming soon.


## Usage

List available Ruby versions with railsexpress patches.

    rbenv install -l | grep railsexpress

Pick a version and install it.

    rbenv install <version>

Follow the [ruby-build instructions](https://github.com/sstephenson/ruby-build).

