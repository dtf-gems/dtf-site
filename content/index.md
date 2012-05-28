# Deryls Testing Framework

DTF is designed to be a modular framework for testing everything from shell scripts, to Ruby, to Rails apps.

DTF is an umbrella which is designed to incorporate multiple sub-gems, each of which provides additional
functionality to DTF. DTF is the master skeleton within which all other dtf-* gems integrate.

## Internal architecture

DTF is designed in such a way that, with the master skepeton in place, one has only to load additional plugins
from any available DTF extension gem to add additional functionality. This can be anything ranging from
additional languages such as Ruby, Python, C, C++, etc, to testing methods and methodologies.

## Current Status

DTF is 100% Alpha quality right now. (For those that don't know what that means, generally this means DTF is
    comprised of code with a vastly high potential for buggy code that may or may not even run. Consider DTF
    to be experimental until further notice. This README will be updated to reflect when DTF reaches a
    'stable' quality.

    DTF will gladly, and willingly, review any Pull Requests sent to us, and incorporate them as they fit with
    the mission goal of DTF. Please bear in mind that DTF is a rolling Project. This means that the definition
    of what DTF is, and how that is implemented is not firmly etched in stone yet, so both of those can, and
    most likely will, change as time passes. If you can deal with that, please, by all means, feel free to
    contribute.

## Branches

    DTF has a branching and tagging topology as follows, and applies to DTF and _all_ sub-module gems:

    * master - This branch on the DTF control gem, and _all_ dtf-<blah> sub-module gems is for **development**
    
    * stable - This branch on the DTF gem, and _all_ dtf-<blah> sub-modules, is 'stable' or 'production'
    quality. Anything on this branch is to be considered safe and usable for everyday stuff.

    * hotfix/>blah> branches are **stable** quality only. These are for running fixes to a particular stable
    branch and will usually result in generating a new version tag. For example, if the hotfix was applied
    against v2.3.4, then a tag of v2.3.5 would be generated once that hotfix was proven to be tested and
    stable.

    * feature/<blah> branches are **development** quality only. This is for work on individual new features
    that _will_ be rolled into DTF or sub-module gems.

    * playground/<blah> branches are **alpha** quality only. These are for developers to work out either
    feasibilty of way-in-the-future ideas or to try something out that may, or may not, be incorporated into
    the DTF or its sub-modules. _These are 100% to9 be considered throw-aways. They could disappear at any
    moment, and any user of the DTF framework that relies on these branches is on their own. NO SUPPORT will
    be provided of any kind for these branches_ so everyone is clear on that.

    * All 'stable' production releases will be tagged. Only those releases will be tagged starting with a v,
    and a series like #.#.#  where the first '#' starts with 1 going to whatever, in progressive order. This
    represents an industry standard versioning format. NOTE: v0.#.# is NOT considered a 'stable' release!
    This is normal in the industry for Projects just starting out. When a version is reached that we believe
    to be of sufficient quality to be denoted, and tagged, as our first Stable release, it will be marked as
    v1.#.# and NOT v0.#.#. The remaining '#' in the example denote our Minor, and Change '#' levels. For
    example, #.#.# is Major.Minor.Change_Number_within_Minor. This means the following. Given a 'v2.3.4' tag,
    this would denote:
    
      * The 2nd official 'stable' release.
      * The 3rd Minor change to the 2.x series
      * The 4th applied change within the 3rd Minor series.

Until such time as the first official stable release is made, all v0.#.# tags up to but not including v0.5.0
are of Alpha quality. Tags v0.5.# up to but not including v1.0.0 are to be considered Beta quality. This gives
us plenty of room for Alpha _and_ Beta work before an official 'stable' release within the numbering system.
** This applies to the DTF control gem, and _all_ dtf-<blah> sub-module gems! Please bear this in mind! **

We are making this a uniform policy across all levels of DTF to ensure that what you think something is,
really is when it comes to version numbers and what they mean. This _will_ be a _strictly_ enforced policy.


## Installation

To Be Announced


## Usage

To Be Announced


