# Kubernetes 1.18


#### Links

* [This document](https://git.k8s.io/sig-release/releases/release-1.18/README.md)
* [Release Team](https://git.k8s.io/sig-release/releases/release-1.18/release_team.md)
* [Meeting Minutes](http://bit.ly/k8s118-releasemtg) (join [kubernetes-sig-release@] to receive meeting invites)
* [v1.18 Release Calendar][k8s118-calendar]
* Contact: [#sig-release] on slack, [kubernetes-release-team@] on e-mail
* [Internal Contact Info]() (accessible only to members of [kubernetes-release-team@])

#### Tracking docs

* [Enhancements Tracking Sheet](http://bit.ly/k8s-1-18-enhancements)
* Bug Triage Tracking Sheet: TODO
* CI Signal Report: TODO
* [Retrospective Document][Retrospective Document]
* [kubernetes/sig-release v1.18 milestone](https://github.com/kubernetes/kubernetes/milestone/44)

#### Guides

* [Targeting Issues and PRs to This Milestone](https://git.k8s.io/community/contributors/devel/sig-release/release.md)
* [Triaging and Escalating Test Failures](https://git.k8s.io/community/contributors/devel/sig-testing/testing.md#troubleshooting-a-failure)

## tl;dr

The 1.18 release cycle is proposed as follows:

- **Monday, January 06**: Week 1 - Release cycle begins
- **Tuesday, January 28**: Week 4 - [Enhancements Freeze]
- **Thursday, March 05**: Week 9 - [Code Freeze]
- **Monday, March 16**: Week 11 - Docs must be completed and reviewed
- **Tuesday, March 24**: Week 12 - Kubernetes v1.18.0 released


## Timeline


| **What** | **Who** | **Jan** | **Feb** | **Mar** | **Apr** | **WEEK** | **CI SIGNAL** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Start of Release Cycle | Lead | Mon 6 | | | | week 1 | [master-blocking] |
| Start Enhancements Tracking | Enhancements Lead | Tue 7 | | | | | |
| Schedule finalized | Lead | Fri 10 | | | | | |
| Team finalized | Lead | Fri 17 | | | | week 2 | |
| 1.18.0-alpha.2 released | Branch Manager | Tue 21 | | | | | |
| Start Release Notes Draft | Release Notes Lead | Tue 21 | | | | week 3 | |
| **Begin [Enhancements Freeze]** (EOD PST) | Enhancements Lead | Tue 28 | | | | week 4 | [master-blocking], [master-informing] |
| 1.18.0-alpha.3 released | Branch Manager | | Tue 4 | | | week 5 | |
| 1.18.0-alpha.4 released | Branch Manager | | Tue 11 | | | week 6 | |
| release-1.14 jobs removed | Branch Manager | | Tue 18 | | | week 7 | |
| release-1.18 branch created | Branch Manager | | Tue 18 | | | | |
| release-1.18 jobs created | Branch Manager | | Tue 18 | | | | |
| 1.18.0-beta.0 released | Branch Manager | | Tue 18 | | | | |
| **Begin [Burndown]** (MWF meetings) | Lead | | Mon 24 | | | week 8 | [1.18-blocking], [master-blocking], [master-informing] |
| **Call for [Exceptions][Exception]** | Lead | | Mon 24 | | | | |
| Brace Yourself, Code Freeze is Coming | Comms / Bug Triage | | Mon 24 | | | | |
| 1.18.0-beta.1 released | Branch Manager | | Tue 25 | | | | |
| Docs deadline - Open placeholder PRs | Docs Lead | | Fri 28 | | | | |
| **Begin [Code Freeze]** (EOD PST) | Branch Manager | | | Thu 5 | | week 9 | |
| Burndown Meetings daily| Lead | | | Mon 9 | | week 10 | |
| Docs deadline - PRs ready for review | Docs Lead | | | Mon 9 | | | |
| 1.18.0-beta.2 released | Branch Manager | | | Tue 10 | | | |
| Docs complete - All PRs reviewed and ready to merge | Docs Lead | | | Mon 16 | | week 11 | |
| **Begin [Code Thaw]** (EOD PST) | Branch Manager | | | Tue 17 | | | [1.18-blocking] |
| 1.18.0-rc.1 released | Branch Manager | | | Tue 17 | | | |
| **Cherry Pick Deadline** (EOD PST) | Branch Manager | | | Thu 19 | | week 11 | |
| **v1.18.0 released** | Branch Manager | | | Tue 24 | | week 12 | |
| Release retrospective | Community | | | | Thu 16 | | | | |

## Phases

Please refer to the [release phases document](../release_phases.md).

[k8s118-calendar]: https://bit.ly/k8s-release-cal
[Internal Contact Info]: http://bit.ly/k8s118-contacts
[Retrospective Document]: http://bit.ly/k8s118-retro

[release phases document]: ../release_phases.md

[Enhancements Freeze]: ../release_phases.md#enhancements-freeze
[Burndown]: ../release_phases.md#burndown
[Code Freeze]: ../release_phases.md#code-freeze
[Exception]: ../release_phases.md#exceptions
[Code Thaw]: ../release_phases.md#code-thaw

[master-blocking]: https://testgrid.k8s.io/sig-release-master-blocking#Summary
[master-informing]: https://testgrid.k8s.io/sig-release-master-informing#Summary
[1.18-blocking]: https://testgrid.k8s.io/sig-release-1.18-blocking#Summary

[kubernetes-release-team@]: https://groups.google.com/forum/#!forum/kubernetes-release-team
[kubernetes-sig-release@]: https://groups.google.com/forum/#!forum/kubernetes-sig-release
[#sig-release]: https://kubernetes.slack.com/messages/sig-release/

