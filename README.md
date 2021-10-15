# CLI-notes

Homebrew

Install packages
`brew install <package>@x.x.x`

Unlink package
In case you have an unsupported version by Angular (the framework needs a LTS version)

`brew unlink <package>`

Link back:

`brew link node@14` 

Getting "Error: Could not symlink" messages?

`brew link --force --overwrite node@14`


