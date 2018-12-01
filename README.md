# fortune-undertale-determination

Undertale's SAVE point quotes of determination for UNIX fortune

```
The waterfall here seems to flow from the ceiling of the cavern...

Occasionally, a piece of trash will flow through...

and fall into the bottomless abyss below.

Viewing this endless cycle of worthless garbage...

It fills you with determination.
```

## Usage

* Ensure `fortune` is installed on your system

* Download `undertale-determination.dat` and save it to your fortune database directory

  * Your fortune database directory is usually `/usr/share/games/fortune`. If that does not exist, running `fortune -f` will show you where `fortune` looks for its databases.

* Run `fortune undertale-determination`

```
$ fortune undertale-determination
The thought that one day the dog will create the perfect snowdog fills you with determination.
```

## Building

* Ensure that `undertale-determination` is formatted correctly for `fortune`. (Quotes enclosed between lines of `%`)

* Run `strfile undertale-determination` to generate a new `undertale-determination.dat` database

* Follow the steps above to use your new `undertale-determination.dat` with `fortune`

## Advanced Usage

### Display a fortune every new shell

Place the following in your shell's config (i.e. `~/.zshrc`)

```bash
if type fortune > /dev/null; then
  fortune undertale-determination
fi
```

## About

All quotes are taken from the [Undertale Wikia entry for SAVE Point](http://undertale.wikia.com/wiki/SAVE_Point)

## Credits

* [Toby Fox](https://twitter.com/tobyfox) for the amazing [Undertale](https://undertale.com/)
