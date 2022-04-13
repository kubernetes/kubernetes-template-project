# Kubernetes Template Project

The Kubernetes Template Project is a template for starting new projects in the GitHub organizations owned by Kubernetes. All Kubernetes projects, at minimum, must have the following files:

- a `README.md` outlining the project goals, sponsoring sig, and community contact information
- an `OWNERS` with:
  - project leads listed as `approvers` ([docs on `OWNERS` files][owners])
  - contacts for security issues listed as `security_contacts`. The
    [Security Response Committee] will reach out to these for triage
    and handling of incoming issues.  They must agree to abide by the
    [Embargo Policy] and will be removed and replaced if they violate
    that agreement.
- a `CONTRIBUTING.md` outlining how to contribute to the project
- an unmodified copy of `code-of-conduct.md` from this repo, which outlines community behavior and the consequences of breaking the code
- a `LICENSE` which must be Apache 2.0 for code projects, or [Creative Commons 4.0] for documentation repositories, without any custom content

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community page](http://kubernetes.io/community/).

You can reach the maintainers of this project at:

- [Slack](http://slack.k8s.io/)
- [Mailing List](https://groups.google.com/forum/#!forum/kubernetes-dev)

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](code-of-conduct.md).

[owners]: https://git.k8s.io/community/contributors/guide/owners.md
[Creative Commons 4.0]: https://git.k8s.io/website/LICENSE
[Security Response Committee]: https://github.com/kubernetes/committee-security-response
[Embargo Policy]: https://git.k8s.io/security/private-distributors-list.md#embargo-policy)
