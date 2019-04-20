# HCIP
Heterogeneous Computing Improvement Proposal

# Getting started contributing
The [HCIP sample](./HCIP-1.sample.md) is the best place to start. The sample was predominantly derived from the Ethereum/Bitcoin improvement proposal based on the Python improvement proposal system. Fork the repository and add your HCIP to it, using the provided [HCIP markdown template](./HCIP-number.template.md). Submit by creating a Pull Request to the Hetrogeneous Computing Improbement Proposal [HCIPs repository](https://github.com/open-heterogeneous-computing-framework/HCIP).

# Contributing

 1. Review [HCIP-1](./hcip-1.sample.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your HCIP to your fork of the repository. There is a [template HCIP here](hcip-number.template.md).
 4. Submit a Pull Request to OHCF's [HCIPs repository](https://github.com/open-heterogeneous-computing-framework/HCIP).

Your first PR should be a first draft of the final HCIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new HCIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the HCIP as a whole.

If your HCIP requires images, the image files should be included in a subdirectory of the `assets` folder for that HCIP as follow: `assets/hcip-X` (for hcip **X**). When linking to an image in the HCIP, use relative links such as `../assets/hcip-X/image.png`.

When you believe your HCIP is mature and ready to progress past the draft phase, you should do one of two things:

 - **For a Standards Track HCIP of type Core**, ask to have your issue added to the agenda of an upcoming All Dev Team meeting, where it can be discussed for inclusion. If implementers agree to include it, the HCIP editors will update the state of your HCIP to 'Accepted'.
 - **For all other HCIPs**, open a PR changing the state of your HCIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the HCIP - they may close the PR and request that you fix the issues in the draft before trying again.

# HCIP Status Terms
* **Draft** - an HCIP that is undergoing rapid iteration and changes
* **Last Call** - an HCIP that is done with its initial iteration and ready for review by a wide audience
* **Final (non-Core)** - an HCIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Final (Core)** - an HCIP that the dev teams have decide to implement and release in a future hard fork or has already been released in a hard fork
* **Accepted** - a core HCIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author
* **Deferred** - an HCIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.

# Accepted HCIPs

| Number        | Title        | Author | Type  | Layer        | Status / Discussion |
| ------------- | ------------ | ------ | ----- | -------------| ------------------- |
| | | |  | |


Hetrogeneous Computing Improvement Proposals (HCIPs), are technical write-ups that describe suggested changes to the Hetrogenesous Computing related open source projects. Whether a upstream open source project should adopt the HCIP still depends on the community decision of that project.

Every pull request will be reviewed and discussed by volunteer OHCF developers and any developers on Github willing to contribute their well reasoned opinions. Regardless if there is general agreement you are able to use the information generated from the discussion to create a second draft. This can be done by either updating the pull request or submitting a new pull request. This process can be repeated (See figure 1) until the volunteer developer community agrees to add the pull request.

![Figure 1: The cyclic process of proposal and review](./process.png "Figure 1: The process of proposal and review")

Having an HCIP within the folder of the repository does not make it a formally accepted standard until its status becomes Active. For an HCIP to become Active requires the mutual consent of the community.


# References
* [EIP Process](https://github.com/ethereum/EIPs)
* [ECIP Process](https://github.com/ethereumclassic/ECIPs)
* [TAP Process](https://github.com/theupdateframework/taps/blob/master/tap1.md)


