# Installation guide

1. Install homebrew by visiting https://brew.sh
2. Run following commands in Terminal.app and follow their output

```
# Login to github command line
$ brew install gh
$ gh auth login

# Get the project and git submodules
$ mkdir Projects
$ gh repo clone travelingvanproblem/site Projects/travelingvanproblem -- --recursive
$ cd Projects/travelingvanproblem
```

3. Install needed dependencies for the project:

```
$ brew install asdf
# setup asdf by following the output
$ asdf plugin add hugo
$ asdf plugin add golang
$ asdf install
```

4. Start running the web server locally to see how your changes would look like for other users

```
$ cd ~/Projects/travelingvanproblem
$ hugo server
```

