# Blog

I assume you are running Ruby. I'm running this on `ruby 2.2.1p85 (2015-02-26 revision 49769) [x86_64-linux]`, running on Ubuntu 14.04.3 LTS.

To update software sources, simply run `bundle install`.

This blog runs on Jekyll. To run the jekyll server, simply follow the following steps.

1. Open your `~/.zshrc` or `~/.bashrc`.
2. Add the following line to the file and save:
    alias blag='bundle exec jekyll serve --watch --incremental'
3. Run `source ~/.zshrc` or `source ~/.bashrc`.
4. Run `blag`.
