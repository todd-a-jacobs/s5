# S5: A Simple Standards-Based Slide Show System #

## Why is this project here on GitHub?

This project is a continuation of the [S5 project][s5] created by Eric
A. Meyer. The original project was placed into the public domain (see
[the license document][license] for additional details), and has been
unmaintained for a number of years.

Contributors are extremely welcome, but please make sure you read [the
license document][license] carefully, and understand the implications.
It is believed that one of the reasons this great project languished was
because of the overhead involved in tracking public domain grants to the
project, so we sincerely hope we've resolved that issue in a legal,
ethical, and community-friendly way.

If you represent Eric A. Meyer, Kathryn S. Meyer, the [Free Software
Foundation][fsf], or the [Electronic Frontier Foundation][eff] and think
we're metaphorically smoking crack on our licensing, please contact us
immediately. This project certainly believes its licensing to be in good
faith, but there are people who are paid to know more about these things
than we do. :)

## Quick Start

    # Clone the repository.
    git clone git@github.com:CodeGnome/s5.git

    # Copy the template to an appropriately named sub-directory in your
    # web server's DOCUMENT_ROOT.
    cp -a s5/s5-blank /path/to/slideshow

    # Change to the new directory.
    cd /path/to/slideshow

    # Edit the slideshow. Remember to remove any boilerplate in the
    # template. 
    vim index.html

## Documentation

- [S5 FAQ][s5faq]
- [A Basic Primer in Using S5][primer]
- [Full S5 Reference][reference]

## Resources

- The [original S5 archive][v1.1] can be downloaded directly from the
  the meyerweb.com website.
- Additional [themes][themes] are also available.
- There is a [mailing list][list] on Google Groups.

- - - -
[s5]: http://meyerweb.com/eric/tools/s5/
[s5faq]: http://meyerweb.com/eric/tools/s5/faq.html
[primer]: http://meyerweb.com/eric/tools/s5/primer.html
[reference]: http://meyerweb.com/eric/tools/s5/structure-ref.html
[license]: http://github.com/CodeGnome/s5/blob/master/LICENSE.md
[v1.1]: http://meyerweb.com/eric/tools/s5/v/1.1/s5-11.zip
[themes]: http://meyerweb.com/eric/tools/s5/themes/
[list]: http://groups.google.com/group/s5project
[eff]: http://www.eff.org/
[fsf]: http://www.fsf.org/
