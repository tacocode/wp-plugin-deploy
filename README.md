# WP Plugin Deploy

Automated SVN deployment of your Git versioned WordPress plugin

## Installation

1. Copy `wp-plugin-deploy.sh` to the root of your Git repo
2. Adjust the vars `PLUGINSLUG`, `MAINFILE` & `SVNUSER` to match the plugin/SVN repo
3. Within the root of your Git repo, run `chmod +x wp-plugin-deploy.sh`

## Usage

Once you are ready to release a new version to the WordPress plugin repository, simply run `./wp-plugin-deploy.sh` in your CLI. You will be optionally offered to create a Git commit & tag if you haven't done so already.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Issues / Bugs

Please use the [issue tracker](https://github.com/thehelvetian/wp-plugin-deploy/issues)

## Credits

This is a modification of Brent Shepherd's deploy script as found [here](https://github.com/thenbrent/multisite-user-management/blob/master/deploy.sh) which is a modification of Dean Clatworthy's deploy script as found [here](https://github.com/deanc/wordpress-plugin-git-svn)

## License

[MIT License](https://github.com/thehelvetian/wp-plugin-deploy/blob/master/LICENSE)