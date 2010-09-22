# Overview

This module, for Drupal 7, exposes fields as tokens.

E.g., a `field_expiration` field will be exposed as `[node:field_expiration]`.

This is a temporary, and very limited solution till this feature is implemented
by either CCK or Token. This module doesn't try to be very useful.

## Downloading

You may [download this module as a zip or tar file](http://github.com/mooffie/simple-field-tokens/archives/master).

## Alternatives

- Wolfgang Ziegler's [Entity](http://drupal.org/project/entity) module.

## See also

- http://drupal.org/node/691078 for a discussion about this functionality.

## The status of this module

I wrote this module for one reason only: I was [working on a Field API related
feature](http://drupal.org/node/917576) for the [Flag](http://drupal.org/project/flag)
module and I wanted to demonstrate its usefulness. This module is very minimal
(e.g., it emites tokens as plain text only) and it's going to stay this way:
I'm going to remove this module as soon as somebody comes up with a better one.
I'm not going to publish this module on Drupal.Org or advertize it in any other
way.

