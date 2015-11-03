# draft-XXXX-rfc4880-bis

This repository is for the development of a IETF draft for the
[OPENPGP working group](http://datatracker.ietf.org/wg/openpgp/charter/).

## Links

* IETF Page: <TBD>
* Mailing List: https://www.ietf.org/mailman/listinfo/openpgp
* Issue Tracking: https://github.com/openpgp/4880-bis/issues

## Issue States

The following labels are used in the issue tracker for issues
in the "open" state:

* NEW:  A submitted issue
* OPEN: An accepted issue open to discussion
* DEAD: A rejected issue closed to discussion
* VERIFY: An open issue with a solution proposal that needs to be
  verified on the mailing list
* EDIT: The issue is waiting for the document editor(s) to make the
  corresponding changes
* REVIEW: The edits have been done and the updated I-D need to be
  reviewed
* DONE: The edits have been reviewed and the issue has been resolved

## Contributing

Before submitting feedback, please familiarize yourself with our
current issues
list and review the
[working group home page](http://datatracker.ietf.org/wg/openpgp/charter/). If
you're new to this, you may also want to read the [Tao of the
IETF](https://www.ietf.org/tao.html).

Be aware that all contributions to the specification fall under the
[NOTE WELL](#note-well) and the [IETF IPR statement](#ipr)
terms outlined below.

1. The best way to provide **design** feedback and ask
questions is
sending an e-mail to
[our mailing list](https://www.ietf.org/mailman/listinfo/openpgp). This
will ensure that the entire Working Group sees your input in a timely
fashion.

2. If you have **editorial** suggestions (*i.e.*, those that do not
   change the meaning of the specification), you can either:

  a) Fork this repository and submit a pull request; this is the
  lowest friction way to get editorial changes in.

  b) Submit a new issue to Github, and mention that you believe it is
  editorial in the issue body. It is not necessary to notify the
  mailing list for editorial issues.

  c) Make comments on individual commits in Github. Note that this
  feedback is processed only with best effort by the editors, so it
  should only be used for quick editorial suggestions or questions.

3. For non-editorial (*i.e.*, **design**) issues, you can also create an
   issue on Github. However, you **must notify the mailing list** when
   creating such issues, providing a link to the issue in the message
   body.

> Note that **github issues are not for substantial discussions**; the
> only appropriate place to discuss design issues is on the mailing
> list itself.

## NOTE WELL

Any submission to the [IETF](https://www.ietf.org/) intended by the
Contributor for publication as all or part of an IETF Internet-Draft
or RFC and any statement made within the context of an IETF activity
is considered an "IETF Contribution". Such statements include oral
statements in IETF sessions, as well as written and electronic
communications made at any time or place, which are addressed to:

* The IETF plenary session
* The IESG, or any member thereof on behalf of the IESG
* Any IETF mailing list, including the IETF list itself, any working
  group or design team list, or any other list functioning under IETF
  auspices
* Any IETF working group or portion thereof
* Any Birds of a Feather (BOF) session
* The IAB or any member thereof on behalf of the IAB
* The RFC Editor or the Internet-Drafts function
* All IETF Contributions are subject to the rules of
  [RFC 5378](https://tools.ietf.org/html/rfc5378) and
  [RFC 3979](https://tools.ietf.org/html/rfc3979)
  (updated by [RFC 4879](https://tools.ietf.org/html/rfc4879)).

Statements made outside of an IETF session, mailing list or other
function, that are clearly not intended to be input to an IETF
activity, group or function, are not IETF Contributions in the context
of this notice.

Please consult [RFC 5378](https://tools.ietf.org/html/rfc5378) and
[RFC 3979](https://tools.ietf.org/html/rfc3979) for details.

A participant in any IETF activity is deemed to accept all IETF rules
of process, as documented in Best Current Practices RFCs and IESG
Statements.

A participant in any IETF activity acknowledges that written, audio
and video records of meetings may be made and may be available to the
public.

## IPR

Copyright (c) 2015 IETF Trust and the persons identified as the
document authors. All rights reserved. 

This document is subject to BCP 78 and the IETF Trust's Legal
Provisions Relating to IETF Documents
(https://trustee.ietf.org/license-info) in effect on the date of
publication of this document. Please review these documents carefully,
as they describe your rights and restrictions with respect to this
document. Code Components extracted from this document must include
Simplified BSD License text as described in Section 4.e of the Trust
Legal Provisions and are provided without warranty as described in the
Simplified BSD License.

## Directory Structure

directory    | contents 
---          | ---
src/         | markdown source  
out/txt/     | ID-formated ascii
out/pdf/     | ID-formated PDF  
out/html/    | ID-formated HTML 
out/xml/     | RFC2629 XML      

## Git workflow

### Forks and Pull Requests

The editor(s) of the document will retain control of upstream repo
found at https://github.com/openpgp/4880-bis.

As mentioned in [Contributing](#Contributing), anyone wishing to edit
the document should fork the upstream repo and make their edits, then
issue a pull request (and reference the github issue(s) they are
addressing, if any).  The editor(s) will then evaluate the pull
request and either accept it, or suggest changes.

Conflicts between the contributor and the editor, if unable to be
resolved, should be brought to the attention of the working group
and/or the co-chairs at openpgp-chairs@ietf.org.

### Branches

The repo will consist of at least two branches.

* *rel* will be the most recent  document release and will be tagged as
  per IETF process (00, 01, etc.).

* *can* will be the current working version.  Edits should be done in
  *can* and **NOT** in release.  The editor(s) will, in consultation
  *with the contributors decide when to merge the *can* into
  **rel* and *issue* a new ID.

## Markdown tooling

TBD
