## Running locally
Jekyl requires `ruby` v2.4+
```
ruby -v
```
Update ruby to 2.4+ (if not currently). There's a `rbenv` version file `.ruby-version` in the root which should set your ruby version to `2.6.3`

https://github.com/rbenv/rbenv#command-reference

Make sure ruby gems for 2.6 are in your PATH
```
export PATH=$HOME/.gem/ruby/2.6.0/bin:$PATH
```
```
jekyll serve
```
