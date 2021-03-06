# mbp-initial-set-up
A repo to help anyone set up a dev environment on a new macbook

This includes:
- slack
- postman
- vs code
- zoom
- pgadmin4
- git
- yarn
- zsh
- gpg
- postgresql

## Apps 
```
$brew install —cask appname

appnames:
	slack
	postman
	visual-studio-code
	zoom
	pgadmin4
```

Check brew.sh if there are any issues, command could’ve been changed

## Tech
```$brew install 

run the above command with each word below:
	git
	yarn
	zsh
	gpg
	postgres
$brew services start postgresql
$createdb
```

## RVM
- New command for RVM (new maintainer)

```gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB```

```\curl -sSL https://get.rvm.io | bash -s stable --rails```

to check version of rvm and ensure it installed correctly
```$rvm -v ```


## Install Ruby and Rails

Check ruby website to check for latest stable version

```$rvm install 3.0.1(version number)```

```$gem install rails```
