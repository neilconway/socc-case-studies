socc-case-studies
=================

This package contains the source code for the case studies in our SoCC'12 paper
on "Logic and Lattices for Distributed Programming". The kvs/ and cart/
subdirectories contain code that corresponds to the case studies presented in
Sections 5 and 6, respectively.

Note that to execute these programs, you'll need a version of Bud that has
support for lattices. You can find this by cloning the Bud git repository and
installing Bud from source:

    https://github.com/bloom-lang/bud

To run the unit tests included with this tarball:

    cd test; ruby all_tests.rb

Note that the unit tests require the "minitest" gem to be installed.
