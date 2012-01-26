# Scala Documentation #

This repository contains the source for the Scala documentation website, as well as the source for "Scala Improvement Process" (SIP) documents. 

## Contributing ##

Please have a look at [http://docs.scala-lang.org/contribute.html](http://docs.scala-lang.org/contribute.html) before making a contribution. 
This document gives an overview of the type of documentation contained within the Scala Documentation repository and the repository's structure.

Small changes, or corrected typos will generally be pulled in right away. Large changes, like the addition of new documents, or the rewriting of 
existing documents will be thoroughly reviewed-- please keep in mind that, generally, new documents must be very well-polished, complete, and maintained 
in order to be accepted.

## Dependencies ##

### Unix ###

Jekyll is required. Follow the install instructions at the Jekyll [wiki](https://github.com/mojombo/jekyll/wiki/Install). In most cases, you can install via RubyGems: 

    gem install jekyll

OSX users might need to update RubyGems:

    sudo gem update --system

### Windows ###

Grab the [RubyInstaller](http://rubyinstaller.org/downloads). Try release 1.8.x if you experience unicode problems with 1.9.x.

Follow the instructions for [RubyInstaller DevKit](https://github.com/oneclick/rubyinstaller/wiki/Development-Kit).

Install Jekyll using the gem package manager:

    gem install jekyll

## Building & Viewing ##

cd into the `scala.github.com` directory, and build by:

    jekyll --server

The generated site is available at `http://localhost:4000`

## Markdown ##

The markdown used in this site uses [Maruku](http://maruku.rubyforge.org/maruku.html) extensions.

## License ##

All documentation contained in this repository is licensed by EPFL under a Creative Commons Attribution-Share Alike 3.0 Unported license ("CC-BY-SA"), unless otherwise noted. By submitting a "pull request," or otherwise contributing to this repository, you implicitly agree to license your contribution under the above CC-BY-SA license. The source code of this website is licensed to EPFL under the [Scala License](http://www.scala-lang.org/node/146), unless otherwise noted. 




