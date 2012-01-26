Welcome to Vinculum.

Vinculum is a Drupal 7 implementation for the pingback and trackback protocols.

Functionllity:
- support pingback and trackback
- register one pingback/trackback per node per link

Vinculum: latin for a link in a chain (and coincidentally the heart of a Borg ship)

INSTALLATION INSTRUCTIONS FOR Vinculum

(1) Download the tarball to your 'modules' directory

(2) Extract the tarball with

      "tar -xvzf vinculum-7.x-X.Y.tar.gz"

    where the 'X' and 'Y' should be the digits that
    are in the exact name of the tarball you've downloaded.

(3) Log in to your Drupal site as someone with permission
    to enable modules and enable trackback.

(4) Configure Vinculum for each content type. Send and Receive is enabled for
    all content types by default.
    Configure the global settings on admin/config/content/vinculum.

Reports of sent and received vinculums (pingbacks or trackbacks) are available
on admin/reports/vinculum.


TECHNICAL REFERENCES:

Pingback specification
- http://www.hixie.ch/specs/pingback/pingback

Trackback specification
- http://www.sixapart.com/pronet/docs/trackback_spec
