
# Ivy

Ivy is a static website generator built in Python. It's small, elegant, and easy to use➡https://www.dmulholl.com/docs/ivy-dev/.

    $ ivy --help

    Usage: ivy [FLAGS] [COMMAND]

      Ivy is a static website generator. It transforms a directory of text
      files into a self-contained website.

    Flags:
      --help              Print the application's help text and exit.
      --version           Print the application's version number and exit.

    Commands:
      build               Build the site.
      clear               Clear the output directory.
      init                Initialize a new site directory.
      serve               Run a web server on the site's output directory.
      tree                Print the site's node tree.
      watch               Monitor the site directory and rebuild on changes.

    Command Help:
      help <command>      Print the specified command's help text and exit.

Contributing
My goal is to keep Ivy as small and simple as possible so I almost certainly won't accept pull requests. Ivy's plugin system makes it extremely flexible, however, so there's a good chance any feature you want to add can be written as an extension. (Let me know if you find you need an extra event or filter hook to make an extension work.)


* [Documentation](http://mulholland.xyz/docs/ivy/)
* [Demo Site](http://ivy.mulholland.xyz/graphite/)

License
This work has been placed in the public domain.
