Games-FrozenBubble is Copyright © 2000-2012, The Frozen-Bubble Team.

# NAME

README - basic information for users prior to downloading


# INSTALLATION

## system-wide installation

    perl Build.PL
    ./Build
    ./Build test
    sudo ./Build install

## installation in a private directory

    perl Build.PL INSTALL_BASE=~/modules_prefix
    ./Build
    ./Build test
    ./Build install

Do not forget to add F<$HOME/modules_prefix/lib/perl5> to your C<@INC>, see
L<perlfaq8/"How do I add a directory to my include path (@INC) at runtime?">.


# DEPENDENCIES

## Pango development files

C<libpango1-dev> and C<pkg-config> are required.

    sudo apt-get install libpango1-dev
    sudo zypper install pango-devel pkg-config

Users of Strawberry Perl for Windows need not worry.

## Alien::SDL

### Unix/Linux/Macs

You may need the following packages:

    libpng-dev libvorbis-dev x11proto-xext-dev libxft-dev               # deb
    libpng-devel libvorbis-devel xorg-x11-libXext-devel xorg-x11-devel  # rpm

During configuration of C<Alien::SDL>, it is B<critical> to select Pango support.

## Perl modules

The other numerous module dependencies are listed in F<META.yml> (online at
L<http://search.cpan.org/dist/Games-FrozenBubble/META.yml>).


# LICENCE AND COPYRIGHT

Copyright © 2000-2012, The Frozen-Bubble Team

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2, as
published by the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

## Disclaimer of warranty

This library is distributed in the hope that it will be useful, but without
any warranty; without even the implied warranty of merchantability or fitness
for a particular purpose.
