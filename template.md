# Adding a New Feature

This template provides a common structure for adding documentation of
newly developed features. The goal is to provide as much information
as possible. The is meant to be a living repository of information
so everyone can, and should, update the documnetation as needed.

Step 1, determine which idocumentation section (i.e. SEV, CXL, ...)
the feature fits in. If a section doesn't exist ithat nicely fits the
feature it can be put in the general section or a new section can be
created.

Step 2, fill out the template, add it to the selected section, and
open a pull request.

**Feature Name**

The feature name should be simple and easy, think along the lines of
what one sees in the output of `git log --one-line`.

**About**

This should be followed by a brief description of this feature, this
information could be pulled directly from a Jira ticket or commit
message.

**Reference**

Provide references to any existing public documnentation, kernel docs,
or mailing list discussions (i.e. lore.kernel.org).

**Usage**

Provide a description on how to use this feature.

**Enablement**

Provide any documentation on how to enable this feature.
* kernel config options (enabled by default?)
* kernel cmdline options
* sysfs interface
* Is this a debug feature? how to enable debug output?

**Platform**

Is this feature platform specific? Genoa? Milan?

**Dependencies**

Does this feature have any dependencies such as previously upstreamed
features?

**Upstream Commit IDs**

Provide a list of the upstream commit IDs.

**Distro Inclusion**

Provide Linux distribution inclusion references for which distro releases this
feature first appears in.

**Testing**

Provide pointers to any existing test suites or an explanation on
how one could test this feature.
