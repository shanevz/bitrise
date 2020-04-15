::: {#page}
::: {#main .aui-page-panel}
::: {#main-header}
::: {#breadcrumb-section}
1.  [Projects](index.html)
:::

[ Projects : SLA for Verified Step Authors ]{#title-text} {#title-heading .pagetitle}
=========================================================
:::

::: {#content .view}
::: {.page-metadata}
Created by [ Krisztian Godrei]{.author}, last modified on Feb 06, 2020
:::

::: {#main-content .wiki-content .group}
**Verified Steps** are marked differently from Community Steps to
communicate towards Bitrise users that they can expect: *secure*,
*maintained*, *consistent*, *high-quality* Steps, which *follows the
Step Development Guideline* and the *underlying tool/service changes* so
that our users\' expectations can be met.

These badges appear on all interfaces we display steps (workflow editor,
[integrations page, ...)]{.inline-comment-marker
ref="b9d7ec4d-050e-4984-8909-752f730d8d9e"}.

------------------------------------------------------------------------

SLA {#SLAforVerifiedStepAuthors-SLA}
---

**First response time:** The time it can take the reporter is notified
about the type ([`critical-bug`, ]{.inline-comment-marker
ref="a21005d3-8b46-4ed3-aecc-4d252a69d7ca"}`bug`, `feature-request`,
`maintenance`) and status ([`accepted`,
`rejected`]{.inline-comment-marker
ref="4759d156-fb37-4c4b-ad08-315a611fc7c3"}) of the Contribution.

**Resolution time:** The time it can take the accepted Contribution gets
closed.

The **type of contribution** needs to be marked by adding one of the
following labels:

-   `critical-bug`: the current feature set has abnormal behavior, which
    blocks users in use of the step (no workaround exists for the
    issue) - must be fixed by the author

-   `bug`: the current feature set has abnormal behavior, which does not
    block users in use of the step (workaround exists for the issue) -
    must be fixed by the author

-   `feature-request`: request for not yet existing feature for step -
    the author can decide whether the feature is worth to implement or
    not

-   `maintenance`: improvement on the step source code, which does not
    add new feature/fixes issue - the author can decide whether the
    feature is worth to implement or not

If a contribution is `rejected`, it needs to be closed within the First
response time.

`accepted` contribution means that the given:
`critical-bug`, `bug`, `feature`, `maintenance` will be fixed/merged,
within the given resolution time.

::: {.table-wrap}
+-----------------------+-----------------------+-----------------------+
| **Type**              | **First response      | **Resolution time**   |
|                       | time**                |                       |
+=======================+=======================+=======================+
| -   `critical-bug`    | 5 business days       | 10 business days      |
+-----------------------+-----------------------+-----------------------+
| -   `bug`             | 5 business days       | 15 business days      |
+-----------------------+-----------------------+-----------------------+
| -   `feature-request` | 5 business days       | 20 business days      |
+-----------------------+-----------------------+-----------------------+
| -   `maintenance`     | 5 business days       | 20 business days      |
+-----------------------+-----------------------+-----------------------+
:::

**Labeling Contributions**

-   add contribution type label to Issues and Pull Requests
    (`critical-bug`, `bug`, `feature`, `maintenance`)

-   rejected contribution means that the given:

    -   `critical-bug`, `bug` is not an abnormal behavior

    -   `feature`, `maintenance` does not worth to implement

    -   any rejection needs to explain to the contributor

    -   any rejected contribution needs to be closed at the first
        response

------------------------------------------------------------------------

Tracking the SLA {#SLAforVerifiedStepAuthors-TrackingtheSLA}
----------------

We expect our users to contribute to steps by opening an Issue or Pull
Request for the step repository.

Verified Steps need to be stored either on Github, Bitbucket or Gitlab.

In the case of the **first response time**, we track whether the
Verified Step author responded to the Contribution and labeled it
(`critical-bug`/`bug`/`feature-request`/`maintenance`) within the set
response time.

In the case of **resolution time**, we check whether the `accepted`
Contribution is closed or not within the set resolution time.

------------------------------------------------------------------------

Enforcing the SLA {#SLAforVerifiedStepAuthors-EnforcingtheSLA}
-----------------

1.  When the issue/violation is detected we notify the Verified Step
    maintainer. If they resolve it then everything\'s good.

2.  If we notify them multiple times and they still fail to resolve the
    issue they\'d lose the Verified Step badge and the step would be
    converted to a \"regular\" step.
:::
:::
:::

::: {#footer role="contentinfo"}
::: {.section .footer-body}
Document generated by Confluence on Apr 15, 2020 15:27

::: {#footer-logo}
[Atlassian](http://www.atlassian.com/)
:::
:::
:::
:::
