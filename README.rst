###########################
Purpose of STScI-MIRI Space
###########################

The goal of this github organization is to have a central location to store
repositories of code used by the STScI MIRI team as part of
carrying out their functional MIRI related duties.

Having a central location for such code provides for long-term
curation, backup, and team ownership of the code.  In addition it encourages more efficent development
of code by taking advantage of the expertise of multiple team members.

STScI-MIRI is classified as an educational organization, and therefore
can create unlimited private repositories.

Space Organization
==================

A subset of the team members have the responsiblity to manage
the space and provide guidence and training to all team members
on effective use of this space, git/github, and
distributed team-based code development.  Space ownership is divided between two or
more MIRI team members to ensure administrative support in the event
of one person being unavailable.

All members are required to use two-factor authentication when working
with repositories within the STScI-MIRI space.

Linked Data Directories
=======================

Since github is not an appropriate location for large data files, a data directory has been set up
on central store at /ifs/jwst/wit/miri/gitdata/STScI-MIRI/ that may be used for input/output 
linked to code located in this github space.

Some code may make use of environmental variables to set filepaths accordingly when running code
in this repository.  For example, for the 'coordinates' repository there are two environmental
variables:

setenv MIRICOORD_DIR /Users/dlaw/jwcode/STScI-MIRI/coordinates/trunk/
setenv MIRICOORD_DATA_DIR /ifs/jwst/wit/miri/gitdata/STScI-MIRI/coordinates/

MIRICOORD_DIR points to your local checkout of the code.  
MIRICOORD_DATA_DIR points to the corresponding data directory to be used
by code in the repository.

Team Members
============

The STScI Team members can be found at
<https://github.com/orgs/STScI-MIRI/people>.

Additional collaborators outside the STScI MIRI team may be added to specific
repositories as necessary.
