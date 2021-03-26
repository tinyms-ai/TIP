### What is an TIP?

    TIP: 1
    Title: TIP Purpose and Guidelines
    Status: Draft
    Type: Meta
    Author: Your Name <your.email@domain.com>
    Created: 2019-04-20

### Abstract
TIP stands for TinyMS Improvement Proposal. Each TIP is a design document providing information to the TinyMS community, or describing a new feature for TinyMS ecosystem or its processes or environment. The TIP should provide a concise technical specification of the feature and a rationale for the feature.  The TIP author is responsible for building consensus within the community and documenting dissenting opinions.

### Motivation
We intend TIPs to be the primary mechanisms for proposing new features, for collecting community input on an issue and for documenting the design decisions that have gone into TinyMS ecosystem. Because the TIPs are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.

### Specification
#### TIP Types
There are three kinds of TIP:

* A Standard Track TIP describes any change that affects most or all TinyMS ecosystem implementations, which can be broken down into the following categories.

**TinyMS

**Model Spec

**Rusted AI


* An Informational TIP describes an TinyMS ecosystem design issue, or provides general guidelines or information to the OHCF community, but does not propose a new feature. Informational TIPs do not necessarily represent the OHCF community consensus or a recommendation, so users and implementors are free to ignore Informational TIPs or follow their advice.

* A Meta TIP describes a process surrounding TinyMS ecosystem or proposes a change to (or an event in) a process. Meta TIPs are like Standard Track TIPs but apply to areas other than the TinyMS ecosystem related development itself. They may propose an implementation, but not to TinyMS ecosystem's codebase; they often require community consensus; unlike Informational TIPs, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in TinyMS ecosystem development.

#### TIP Work Flow
The TIP repository Collaborators change the TIPs status. Please send all TIP-related email to the TIP Collaborators, which are listed under TIP Editors below. Also see TIP Editor Responsibilities & Workflow.

The TIP process begins with a new idea for TinyMS ecosystem. It is highly recommended that a single TIP contain a single key proposal or new idea. Small enhancements or patches that don't affect consensus often don't need an TIP and can be injected into the TinyMS ecosystem development workflow with a patch submission to the corresponding TinyMS ecosystem issue tracker. The more focused the TIP, the more successful it tends to be. The TIP Editor reserves the right to reject TIP proposals if they appear too unfocused or too broad. If in doubt, split your TIP into several well-focused ones.

Each TIP must have a champion -- someone who writes the TIP using the style and format described below, shepherds the discussions in the appropriate forums, and attempts to build community consensus around the idea. The TIP champion (a.k.a. Author) should first attempt to ascertain whether the idea is TIP-able. Opening an [Issue](https://github.com/tinyms-ai/TIP/issues) is the best way to go about this.

Vetting an idea publicly before going as far as writing an TIP is meant to save the potential author time. Asking the OHCF community first if an idea is original helps prevent too much time being spent on something that is guaranteed to be rejected based on prior discussions (searching the Internet does not always do the trick). It also helps to make sure the idea is applicable to the entire community and not just the author. Just because an idea sounds good to the author does not mean it will work for most people in most areas where TinyMS ecosystem is used.

Once the champion has asked the OHCF community as to whether an idea has any chance of acceptance, a draft TIP should be presented as a Pull Request. This gives the author a chance to flesh out the draft TIP; to make properly formatted, of high quality, and to address initial concerns about the proposal.

If the TIP collaborators approves, the TIP editor will assign the TIP a number, label it as Standards Track, Informational, or Process, give it status "Draft", and add it to the git repository. The TIP editor will not unreasonably deny an TIP. Reasons for denying TIP status include duplication of effort, being technically unsound, not providing proper motivation or addressing backwards compatibility, or not in keeping with the TinyMS ecosystem philosophy.

The TIP author may update the Draft as necessary in the git repository. Updates to drafts may also be submitted by the author as pull requests.

Standards Track TIPs consist of three parts, a design document, implementation and finally if warranted an update to the [formal specification](https://github.com/tinyms-ai/model-spec). The TIP should be reviewed and accepted before an implementation is begun, unless an implementation will aid people in studying the TIP. Standards Track TIPs must be implemented in at least two viable TinyMS ecosystem clients before it can be considered Final.

TIP authors are responsible for collecting community feedback on an TIP before submitting it for review. However, wherever possible, long open-ended discussions should be avoided. Strategies to keep the discussions efficient include: having the TIP author accept private comments in the early design phases, setting up a wiki page or git repository, etc. TIP authors should use their discretion here.

For an TIP to be accepted it must meet certain minimum criteria. It must be a clear and complete description of the proposed enhancement. The enhancement must represent a net improvement. The proposed implementation, if applicable, must be solid and must not complicate the protocol unduly.

Once an TIP has been accepted, the implementations must be completed. When the implementation is complete in at least two viable clients and accepted by the community, the status will be changed to "Final". An update to the [formal specification](https://github.com/tinyms-ai/model-spec) should accompany the "Final" status change.

An TIP can also be assigned status "Deferred". The TIP author or editor can assign the TIP this status when no progress is being made on the TIP. Once an TIP is deferred, the TIP editor can re-assign it to draft status.

An TIP can also be "Rejected". Perhaps after all is said and done it was not a good idea. It is still important to have a record of this fact.

TIPs can also be superseded by a different TIP, rendering the original obsolete. This is intended for Informational TIPs, where version 2 of an API can replace version 1.

The possible paths of the status of TIPs are as follows:

<img src=./process.png>

Some Informational and Process TIPs may also have a status of "Active" if they are never meant to be completed. E.g. TIP 1 (this TIP).

#### What belongs in a successful TIP?
Each TIP should have the following parts:

* Preamble -- RFC 822 style headers containing metadata about the TIP, including the TIP number, a short descriptive title (limited to a maximum of 44 characters), the names, and optionally the contact info for each author, etc.

* Abstract -- a short (~200 word) description of the technical issue being addressed.

* Specification -- The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current TinyMS ecosystem platforms (OCP, OpenStack, Kubernetes, RISC-V, ...).

* Motivation -- The motivation is critical for TIPs that want to change the TinyMS ecosystem related Implementations. It should clearly explain why the existing protocol specification is inadequate to address the problem that the TIP solves. TIP submissions without sufficient motivation may be rejected outright.

* Rationale -- The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages.

* The rationale should provide evidence of consensus within the community and discuss important objections or concerns raised during discussion.

* Backwards Compatibility -- All TIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The TIP must explain how the author proposes to deal with these incompatibilities. TIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

* Implementations -- The implementations must be completed before any TIP is given status "Final", but it need not be completed before the TIP is accepted. It is better to finish the specification and rationale first and reach consensus on it before writing code.

#### TIP Formats and Templates
TIPs should be written in markdown format. Image files should be included in a subdirectory for that TIP.

#### TIP Header Preamble
Each TIP must begin with an RFC 822 style header preamble. The headers must appear in the following order. Headers marked with "* " are optional and are described below. All other headers are required.

      TIP: <TIP number>
      Title: <TIP title>
      Author: <list of authors' real names and optionally, email address>
    * Discussions-To: <email address>
      Status: <Draft | Active | Accepted | Deferred | Rejected |
               Withdrawn | Final | Superseded>
      Type: <Standards Track | Informational  Meta>
      Created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
    * Replaces: <TIP number>
    * Superseded-By: <TIP number>
    * Resolution: <url>

The Author header lists the names, and optionally the email addresses of all the authors/owners of the TIP. The format of the Author header value must be

  Random J. User <address@dom.ain>

if the email address is included, and just

  Random J. User

if the address is not given.

If there are multiple authors, each should be on a separate line following RFC 2822 continuation line conventions.

Note: The Resolution header is required for Standards Track TIPs only. It contains a URL that should point to an email message or other web resource where the pronouncement about the TIP is made.

While an TIP is in private discussions (usually during the initial Draft phase), a Discussions-To header will indicate the mailing list or URL where the TIP is being discussed. No Discussions-To header is necessary if the TIP is being discussed privately with the author.

The Type header specifies the type of TIP: Standards Track, Informational, or Meta.

The Created header records the date that the TIP was assigned a number. Both headers should be in yyyy-mm-dd format, e.g. 2001-08-14.

TIPs may have a Requires header, indicating the TIP numbers that this TIP depends on.

TIPs may also have a Superseded-By header indicating that an TIP has been rendered obsolete by a later document; the value is the number of the TIP that replaces the current document. The newer TIP must have a Replaces header containing the number of the TIP that it rendered obsolete.

#### Auxiliary Files
TIPs may include auxiliary files such as diagrams. Such files must be named TIP-XXXX-Y.ext, where "XXXX" is the TIP number, "Y" is a serial number (starting at 1), and "ext" is replaced by the actual file extension (e.g. "png").

#### Transferring TIP Ownership
It occasionally becomes necessary to transfer ownership of TIPs to a new champion. In general, we'd like to retain the original author as a co-author of the transferred TIP, but that's really up to the original author. A good reason to transfer ownership is because the original author no longer has the time or interest in updating it or following through with the TIP process, or has fallen off the face of the 'net (i.e. is unreachable or not responding to email). A bad reason to transfer ownership is because you don't agree with the direction of the TIP. We try to build consensus around a TIP, but if that's not possible, you can always submit a competing TIP.

If you are interested in assuming ownership of a TIP, send a message asking to take over, addressed to both the original author and the TIP editor. If the original author doesn't respond to email in a timely manner, the TIP editor will make a unilateral decision (it's not like such decisions can't be reversed :).

#### TIP Editors
The current TIP editors are
  * All champions identified in the OHCF github organization

#### TIP Editor Responsibilities & Workflow
For each new TIP that comes in, an editor does the following:

* Read the TIP to check if it is ready: sound and complete. The ideas must make technical sense, even if they don't seem likely to be accepted.
* The title should accurately describe the content.
* Edit the TIP for language (spelling, grammar, sentence structure, etc.), markup, code style

If the TIP isn't ready, the editor will send it back to the author for revision, with specific instructions.

Once the TIP is ready for the repository, the TIP editor will:

* Assign an TIP number (almost always just the next available number)

* Accept the corresponding pull request

* List the TIP in [[README.md]]

* Send email back to the TIP author with next step.

Many TIPs are written and maintained by developers with write access to the TinyMS ecosystem codebase. The TIP editors monitor TIP changes, and correct any structure, grammar, spelling, or markup mistakes we see.

The editors don't pass judgment on TIPs. We merely do the administrative & editorial part. Except for times like this, there's relatively low volume.

### Rationale
For TinyMS ecosystem implementers, TIPs are a convenient way to track the progress of their implementation. Ideally each implementation maintainer would list the TIPs that they have implemented. This will give end users a convenient way to know the current status of a given implementation or library.

TIPs are intended to replace the venerable etherpads which described the initial PoC (Proof of Concept) and strike a balance between ease of accessibility and trackablity.

### Implementation
Fork the [TIP repo](https://github.com/tinyms-ai/TIP). Write an TIP using the [TIP markdown template](https://github.com/tinyms-ai/TIP/blob/master/TIP-number.template.md) and initiate a pull request.

### History
This document, recently edited for the specific use of OHCF community, was derived heavily from [https://github.com/bitcoin/bips Bitcoin's BIP-0001] written by Amir Taaki which in turn was derived from [https://www.python.org/dev/peps/ Python's PEP-0001]. In many places text was simply copied and modified. Although the PEP-0001 text was written by Barry Warsaw, Jeremy Hylton, and David Goodger, they are not responsible for its use in the TinyMS ecosystem Improvement Process, and should not be bothered with technical questions specific to, TinyMS ecosystem, or the TIP. Please direct all comments to the TIP editors.
