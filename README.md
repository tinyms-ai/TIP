# TIP
TinyMS Improvement Proposal

# Getting started contributing
The [TIP sample](./TIP-1.sample.md) is the best place to start. The sample was predominantly derived from the Ethereum/Bitcoin improvement proposal based on the Python improvement proposal system. Fork the repository and add your TIP to it, using the provided [TIP markdown template](./TIP-number.template.md). Submit by creating a Pull Request to the Hetrogeneous Computing Improbement Proposal [TIPs repository](https://github.com/tinyms-ai/TIP).

# Contributing

 1. Review [TIP-1](./TIP-1.sample.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your TIP to your fork of the repository. There is a [template TIP here](TIP-number.template.md).
 4. Submit a Pull Request to TinyMS's [TIPs repository](https://github.com/tinyms-ai/TIP).

Your first PR should be a first draft of the final TIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new TIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the TIP as a whole.

If your TIP requires images, the image files should be included in a subdirectory of the `assets` folder for that TIP as follow: `assets/TIP-X` (for TIP **X**). When linking to an image in the TIP, use relative links such as `../assets/TIP-X/image.png`.

When you believe your TIP is mature and ready to progress past the draft phase, you should do one of two things:

 - **For a Standards Track TIP of type Core**, ask to have your issue added to the agenda of an upcoming All Dev Team meeting, where it can be discussed for inclusion. If implementers agree to include it, the TIP editors will update the state of your TIP to 'Accepted'.
 - **For all other TIPs**, open a PR changing the state of your TIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the TIP - they may close the PR and request that you fix the issues in the draft before trying again.

# TIP Status Terms
* **Draft** - an TIP that is undergoing rapid iteration and changes
* **Last Call** - an TIP that is done with its initial iteration and ready for review by a wide audience
* **Final (non-Core)** - an TIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Final (Core)** - an TIP that the dev teams have decide to implement and release in a future hard fork or has already been released in a hard fork
* **Accepted** - a core TIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author
* **Deferred** - an TIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.

# Accepted TIPs

| Number        | Title        | Author | Type  | Layer        | Status / Discussion |
| ------------- | ------------ | ------ | ----- | -------------| ------------------- |
| | | |  | |


Hetrogeneous Computing Improvement Proposals (TIPs), are technical write-ups that describe suggested changes to the Hetrogenesous Computing related open source projects. Whether a upstream open source project should adopt the TIP still depends on the community decision of that project.

Every pull request will be reviewed and discussed by volunteer OHCF developers and any developers on Github willing to contribute their well reasoned opinions. Regardless if there is general agreement you are able to use the information generated from the discussion to create a second draft. This can be done by either updating the pull request or submitting a new pull request. This process can be repeated (See figure 1) until the volunteer developer community agrees to add the pull request.

![Figure 1: The cyclic process of proposal and review](./process.png "Figure 1: The process of proposal and review")

Having an TIP within the folder of the repository does not make it a formally accepted standard until its status becomes Active. For an TIP to become Active requires the mutual consent of the community.


# References
* [EIP Process](https://github.com/ethereum/EIPs)
* [ECIP Process](https://github.com/ethereumclassic/ECIPs)
* [TAP Process](https://github.com/theupdateframework/taps/blob/master/tap1.md)
