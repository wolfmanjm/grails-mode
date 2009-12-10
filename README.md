This is a minor mode for handling Grails projects in Emacs.

I have tested this with v23+, it probably doesn't work with older
versions.

Right now the main thing it does is integrate with
[anything](http://www.emacswiki.org/emacs/Anything).

This by itself seems pretty useful.

When you edit a file that is under a standard grails project
structure, it will load grails-mode, and define a key C-ca, which will
display a list of all the relevant files in the grails project.

By typing a pattern you can narrow it to all controllers or views or
taglobs etc, or all the files related to "post" for instance, which
would show the PostController, all the view files related to posts the
Post domain etc.

I plan to add quick jump features to it so you can jump to the view
from a controller action etc, like most other IDEs have.

Pair this with
[groovy-mode](http://svn.groovy.codehaus.org/browse/~raw,r=HEAD/groovy/trunk/groovy/ide/emacs/groovy-mode.el)
and an html-mode it is a pretty good way to edit Grails stuff.

