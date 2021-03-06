---
layout: post
author: fabiand
description: This is the second weekly update from the KubeVirt team.
navbar_active: Blogs
pub-date: September 15
pub-year: 2017
category: updates
comments: true
---

This is the second weekly update from the KubeVirt team.

We are currently driven by

-   Being easier to be used on Kubernetes and OpenShift

-   Enabling people to contribute

<!-- more -->
This week we achieved to:

-   Keep cloud-init data in Secrets (@vossel)
    (<https://github.com/kubevirt/kubevirt/pull/433>)

-   First draft code to get layer 3 network connectivity for VMs
    (@vladikr) (<https://github.com/kubevirt/kubevirt/pull/450>)

-   First draft code for the api server aggregation (@stu-gott)
    (<https://github.com/kubevirt/kubevirt/pull/355>)

-   Add further migration documentation (@rmohr)
    (<https://github.com/kubevirt/user-guide/pull/1>)

In addition to this, we are also working on:

-   Progress on how to integrate with host networking (@rmohr)
    (<https://github.com/kubevirt/kubevirt/pull/367>)

-   Converging multiple ansible playbooks for deployment on OpenShift
    (@petrkotas, @cynepco3hahue, @lukas-bednar)
    (<https://github.com/kubevirt-incubator/kubevirt-ansible>)

-   Initial support for Anti- & Affinity for VMs (@MarSik)
    (<https://github.com/kubevirt/kubevirt/issues/438>)

-   Initial support for memory and cpu mapping (@MarSik)
    (<https://github.com/kubevirt/kubevirt/pull/388>)

-   Discussing VM persistence and ABI stability
    (<https://groups.google.com/d/topic/kubevirt-dev/G0FpxJYFhf4/discussion>)

Take a look at the pulse, to get an overview over all changes of this
week: <https://github.com/kubevirt/kubevirt/pulse>

Finally you can view our open issues at
<https://github.com/kubevirt/kubevirt/issues>

And keep track of events at our calendar
[18pc0jur01k8f2cccvn5j04j1g@group.calendar.google.com](https://calendar.google.com/calendar/embed?src=18pc0jur01k8f2cccvn5j04j1g@group.calendar.google.com)

If you need some help or want to chat you can find us on
<irc://irc.freenode.net/#kubevirt>
