# Spack Enhancement Proposals

SEP stands for Spack Enhancement Proposal. SEPs are written design documents
for new features in Spack. While not all features in Spack should go through
SEPs, there are an increasing number of changes that are hard to track without
the details written down. Writing forces you to make your thoughts concrete in
a way that discussions and telcons do not, and SEPs are for occasions where you
really do need to get all the technical details written down before
implementing.

## Is my thing a SEP?

As a rough guideline, use a SEP when:

* The full scope of changes and their impact affect many parts of Spack;
* Complete technical details are hard to understand in short meetings or
  online discussions;
* Consensus is required among many Spack implementers, users, and contributors;
* Changes will require significant effort (redesigns, API changes, chagnes to
  core data structures);
* The feature will likely affect user workflow; or
* Users are likely to notice and to rely heavily on the proposed feature.

The following are probably not SEPs:

* Adding new command options;
* Fixing a bug;
* Refactoring;
* Performance enhancements that just speed up existing commands; or
* Adding error messages.

## What's in a SEP?

We don't want to restrict too much how you write your SEP, but in general, you
should have the following:

1. A description of the problem the SEP aims to solve;
2. A description of the goals of the SEP;
3. The changes being proposed; and
4. Example use cases.

We don't require these to be in any particular order or mandate a format., but
these elements should be clear in your writeup.

## How do I make a SEP?

1. Make a new file called `sep-xxxx.md` in the `seps/` directory in this
   project, where `xxxx` is the next available zero-padded  SEP number.
2. Title your SEP `SEP-n`, where `n` is the SEP number without zero padding.
3. Write up your SEP!
3. Submit a PR for the initial revision, and start working with people to
   refine your ideas and get consensus.

That's it.

## License

This project is part of Spack. Spack is distributed under the terms of both the
MIT license and the Apache License (Version 2.0). Users may choose either
license, at their option.

All new contributions must be made under both the MIT and Apache-2.0 licenses.

See LICENSE-MIT, LICENSE-APACHE, COPYRIGHT, and NOTICE for details.

SPDX-License-Identifier: (Apache-2.0 OR MIT)

LLNL-CODE-811652
