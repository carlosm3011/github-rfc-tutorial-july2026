---
title: "Using GitHub to Write RFCs in a Smart Way"
abbrev: "GitHub for RFCs"
category: info

docname: draft-carlosm3011-github-tutorial-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
# area: PERSONAL
# workgroup: PERSONAL
keyword:
 - next generation
 - unicorn
 - AI-native
venue:
#  group: WG
#  type: Working Group
#  mail: WG@example.com
#  arch: https://example.com/WG
  github: "carlosm3011/github-rfc-tutorial-july2026"
  latest: "https://carlosm3011.github.io/github-rfc-tutorial-july2026/draft-carlosm3011-github-tutorial.html"

author:
 -
    fullname: Carlos Martinez-Cagnazzo
    organization: ACME, Corp.
    email: carlos.cagnazzo@acme.org

normative:

informative:

...

--- abstract

So I made it to the GitHub for RFC work tutorial. This is a summary of what I learnt in it and what ideas may be useful for other types of work.


--- middle

# Introduction

Useful ideas for using GitHub for document production.


# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Bootstrapping

## Steps:

  - Clone the template by "Martin J Thompson".
  - Edit the name of the md file to have a proper draft name.
  - Fill in as much metadata as possible.
  - Commit

## What will happen next ?

A set of Github actions will be triggered which will reshape the repository, include boilerplate in the document, create a README and a LICENSE file.

# Normal Editing

Edits can be made in-line on Github web or using the GH desktop app. Changes can be either committed or used to create a pull request.

PRs are RECOMMENDED.

# Sending to the datatracker

This is done creating a TAG with the exact name of the draft. This will run the submission process.

# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
