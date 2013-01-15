# import-popwin.el

## Introduction
`import-popwin.el` pops up buffer near by import statements with [popwin.el](https://github.com/m2ym/popwin-el).
We often fix import statements in any languages. `import-popwin.el` helps you in such case.


## Screenshot

![import-popwin-ruby](https://github.com/syohex/emacs-import-popwin/raw/master/image/import-popwin-ruby.png)
![import-popwin-perl](https://github.com/syohex/emacs-import-popwin/raw/master/image/import-popwin-perl.png)


## Requirements

* Emacs 24 or higher
* [popwin.el](https://github.com/m2ym/popwin-el) 0.6


## Basic Usage

Pop up buffer near by import statements

    M-x import-popwin


## Default support mode

* c-mode
* c++-mode


## Add own configuration

```` elisp
(import-popwin:add :mode 'java-mode
                   :regexp "^import\\s-")
````
