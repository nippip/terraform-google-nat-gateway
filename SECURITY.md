
# Security Policy

## Reporting Security Issues

The Provenance team and community take all security bugs in Provenance seriously. 

Thank you for improving the security of Provenance. We appreciate your efforts and responsible disclosure and will make every effort to acknowledge your contributions.

Please report security vulnerabilities to
**[security@provenance.io](mailto:security@provenance.io)**.  *Please avoid opening a public issue on the repository for security issues.*


The Provenance team will send a response indicating the next steps in handling your
report. After the initial reply to your report, the team will keep you informed
of the progress towards a fix and full announcement, and may ask for additional
information or guidance.  For critical problems, you may encrypt your report [see below](https://github.com/nippip/terraform-google-nat-gateway/blob/master/SECURITY.md#encryption-key-for-securityprovenanceio).

In addition, please include the following information along with your report:

* Your name and affiliation (if any).
* A description of the technical details of the vulnerabilities. It is very important to let us know how we can reproduce your findings.
* An explanation of who can exploit this vulnerability, and what they gain when doing so -- write an attack scenario. This will help us evaluate your report quickly, especially if the issue is complex.
* Whether this vulnerability is public or known to third parties. If it is, please provide details.

If you believe that an existing (public) issue is security-related, please send
an email to **[security@provenance.io](mailto:security@provenance.io)**. The email should include the issue ID and
a short description of why it should be handled according to this security
policy.


## Disclosure Policy

When the security team receives a security bug report, they will assign it to a primary handler. This person will coordinate the fix and release process, involving the following steps:

* Confirm the problem and determine the affected versions.
* Audit code to find any potential similar problems.
* Prepare fixes for all releases still under maintenance. These fixes will be released as fast as possible to the project.
* Patch releases are sent to *maybe some email list, or ???.*


#### Encryption key for `security@provenance.io`

If your disclosure is extremely sensitive, you may choose to encrypt your
report using the key below. Please only use this for critical security
reports.

```
-----BEGIN PGP PUBLIC KEY BLOCK-----
I can set up a key via keybase and provide the link here.
-----END PGP PUBLIC KEY BLOCK-----
```

## Comments on this Policy

If you have suggestions on how this process could be improved please submit a pull request or email **[security@provenance.io](mailto:security@provenance.io)**

.
.
.

# QUESTIONS
* Security update policy: How should we communicate security issues and fixes to our project users?  Security mailing list, RSS feed, website with version and patch information?

* Security related configuration:  Best security practices that users should follow when configuring their BC.

* Known security gaps & future enhancements:  What is our legal obligation here?
    It’s important to inform your project users of the security controls that aren’t currently in place. Your users deserve to know the full story so they can make informed decisions about how they use your project.

* VDP: Should we consider a Vulnerability Disclosure Program?
https://www.bugcrowd.com/resources/glossary/vulnerability-disclosure-program-vdp/
