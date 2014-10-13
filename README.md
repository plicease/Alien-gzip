# Alien::gzip

Find or build gzip

# SYNOPSIS

    use Alien::gzip;
    # gzip should now be in your PATH if it wasn't already

# DESCRIPTION

Many environments provide the gzip command, but a few do not.
Using this module in your `Build.PL` (or elsewhere) you can
make sure that gzip will be available.  If the system provides
it, then great, this module is a no-op.  If it does not, then
it will download and install it into a private location so that
it can be added to the `PATH` when this module is used.

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2014 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
