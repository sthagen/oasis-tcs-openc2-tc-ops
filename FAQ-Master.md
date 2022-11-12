# OpenC2 Frequently Asked Questions

> **NOTE:** This markdown document exists to support group review
> and updates to the FAQ list. The questions and answers will be
> ported to the OpenC2.org website [FAQ
> page](https://openc2.org/faq.html) for general public
> visibility.

> **IMPORTANT:**  ***Do not*** embed links the question portion
> of the FAQ, as this breaks the formatting on the OpenC2.org
> website. Only use links in the answer body of the FAQ.

> **NOTE:** Per agreement at the 2 November 2022 working meeting,
> FAQs without answers should not be ported to the OpenC2.org
> website. However, such FAQs are maintained here with a "\* \*
> \* TO BE SUPPLIED \* \* \*" tag as the answer to highlight that
> answers are still needed.

### What is OpenC2?

OpenC2 is a standardized language for machine-to-machine
communications for the command and control of technologies that
provide or support cyber defenses. The [OpenC2 Technical
Committee](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2)
is developing a suite of specifications that define the OpenC2
architecture, language, tailor its use to specific cyber-defense
functions, and specify how to convey OpenC2 messages using
various industry-standard transfer protocols.


### What is the difference between OpenC2 and OASIS?

[OpenC2](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2)
is an open source language, available for use and input across
the cyber-security community. Many open source languages and
technologies benefit from support of standards bodies, to help
guide and champion on-going use and evolution of the software or
technology. OpenC2 is a project under
[OASIS](https://www.oasis-open.org/). OASIS is the
**O**rganization for the **A**dvancement of **S**tructured
**I**nformation **S**tandards, a nonprofit international
consortium that develops open IT standards.

### How is the "suite" of OpenC2 Specifications organized?

As described in the [_OpenC2 Architecture
Specification_](https://docs.oasis-open.org/openc2/oc2arch/v1.0/oc2arch-v1.0.html),
there are multiple types of OpenC2 specifications, meant to be
used in concert:

* The [*OpenC2 Architecture
  Specification*](https://docs.oasis-open.org/openc2/oc2arch/v1.0/oc2arch-v1.0.html)
  describes the fundamental structures of OpenC2.

* The [*OpenC2 Language
  Specification*](https://docs.oasis-open.org/openc2/oc2ls/v1.0/oc2ls-v1.0.html)
  provides the essential elements of the language, the structure
  for Commands and Responses, and the mechanisms for extending
  the OpenC2 language.

* [**OpenC2 Actuator
  Profiles**](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical)
  specify the subset of the OpenC2 language relevant in the
  context of specific actuator functions (e.g., [packet
  filtering](https://docs.oasis-open.org/openc2/oc2slpf/v1.0/oc2slpf-v1.0.html),
  honeypots).

* [**OpenC2 Transfer
  Specifications**](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical)
  utilize existing protocols and standards (e.g.,
  [HTTPS](https://docs.oasis-open.org/openc2/open-impl-https/v1.1/cs01/open-impl-https-v1.1-cs01.html),
  [MQTT](https://docs.oasis-open.org/openc2/transf-mqtt/v1.0/transf-mqtt-v1.0.html))
  to implement OpenC2 message transfer in specific environments.


### What can OpenC2 do for me?

As cyber-defense technology vendors and providers adopt OpenC2,
OpenC2 can dramatically improve incident response to
cyber-threats and allow for enterprise wide interoperability for
cyber-security policy orchestration. Management and development
of cyber-defense responses is simplified and greater
collaboration and integration across a wide range of technologies
is enabled.


### How can I access OpenC2?

OASIS Specifications are open for all to use. The TC's [home page
at
OASIS](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2)
lists the [officially published
specifications](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical).
This website includes a list of all [OpenC2 specifications
(published and under
development)](https://openc2.org/openc2-org.github.io/specifications.html),
and a collection of [open source software
tooling](https://openc2.org/openc2-org.github.io/opensource.html)
to add in implementing OpenC2.


### Do I have to be a member of OASIS to use OpenC2?

No, OASIS OpenC2 specifications are available to all. There are
no known intellectual property rights associated with OpenC2. See
[this page](https://www.oasis-open.org/committees/openc2/ipr.php)
for additional information.

If you desire to participate in the OpenC2 Technical Committee
and draft future specifications, then OASIS membership would be
required.


### How long has this been around?

The OASIS OpenC2 TC was formed in 2017 and the first 3 OpenC2
Specifications were approved in 2019. The OpenC2 TC continues to
develop and improve the specifications in the suite.


### What similar efforts exist?

\* \* \* TO BE SUPPLIED \* \* \*

> TBD pending identification of other "similar efforts"


### Is there an OpenC2 API?

> _NOTE: this FAQ should probably also refer to transfer
> specifications beyond HTTPS. Also, ensure the HTTPS link is
> pointing to the current specification._

The OpenC2 Language Specification and Actuator Profiles taken
together define the request and response message content and
expected actions, and a Transfer Specification defines the
communications method. The exchange of OpenC2 command and
response messages using the [HTTPS Transfer
Specification](https://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html)
can be considered a Remote Procedure Call (RPC)-style Web API.
OpenC2 does not have a Web API defined in terms of
Representational State Transfer (REST).


### What is the TC's process for creating work products?

The OpenC2 TC's process for creating and managing work products
is captured in the TC's [Documentation
Norms](https://github.com/oasis-tcs/openc2-tc-ops/blob/master/Documentation-Norms.md).


### What is the meeting schedule?

The OpenC2 TC holds meetings on Wednesdays at 11:00am Eastern
Time ("OpenC2 Time"). The TC conducts business meetings on the
3rd Wednesday of the month, and working meetings on the 1st, 2nd,
and 4th Wednesdays of each month.  See the [Meeting
Schedule](#https://github.com/oasis-tcs/openc2-tc-ops/blob/main/General-Member-Info.md#meeting-schedules)
portion of the [General Member
Information](https://github.com/oasis-tcs/openc2-tc-ops/blob/main/General-Member-Info.md)
page of our [TC Operations
repository](https://github.com/oasis-tcs/openc2-tc-ops) for more
information.

### How does OpenC2 relate to the OASIS CACAO TC?

The [CACAO (Collaborative Automated Course of Action Operations
for Cyber Security)
TC's](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cacao)
goal is defining the standard for creating machine-readable
course of action playbooks for cybersecurity operations. CACAO
will have the ability of integrating different languages for
controlling components that are part of cyber defense ecosystems,
thus, OpenC2 is a candidate.

### How does OpenC2 relate to STIX Course of Action (COA)?

[Structured Threat Information Expression
(STIX™)](https://oasis-open.github.io/cti-documentation/) is a
language and serialization format used to exchange cyber threat
intelligence (CTI). One of the STIX Domain Objects (SDOs),
[Course of Action
(COA)](https://docs.oasis-open.org/cti/stix/v2.1/os/stix-v2.1-os.html#_a925mpw39txn),
has the ability to capture structured/automated courses of
action. OpenC2 can be utilized to populate STIX COA SDOs for
sharing automated courses of action for the purpose of responding
to cyber incidents in cyber-relevant time.

### How does OpenC2 relate to OpenDXL?

[OpenDXL](https://www.opendxl.com/) is an initiative to create
adaptive systems of interconnected services that communicate and
share information for real-time, accurate security decisions and
actions. As a communications fabric, OpenDXL supports both
point-to-point and publish / subscribe communications models.
OpenDXL could be used as a communications fabric for OpenC2, but
no transfer specification has been formalized for it.

### How does OpenC2 relate to the Open Cybersecurity Alliance?

\* \* \* To Be Supplied \* \* \*

### How does OpenC2 relate to PACE?

Posture Attribute Collection and Evaluation ([PACE](https://opencybersecurityalliance.org/pace/)) is an
[Open Cybersecurity Alliance](https://opencybersecurityalliance.org/)
effort to create a
comprehensive automated strategy for understanding security posture.
OpenC2 plays two roles in PACE.
PACE uses OpenC2 for command & control to obtain security posture information,
and for the command & control of the PACE system itself
(e.g., request security posture evaluation of a device).
OpenC2 also plays a role in implementing the actions
that result from posture evaluation
(e.g., add a firewall rule, sandbox a device, etc).

### How does OpenC2 relate to SCAP?

\* \* \* To Be Supplied \* \* \*

[Security Content Automation Protocol (SCAP)](https://csrc.nist.gov/projects/security-content-automation-protocol)?

### How does OpenC2 relate to the OCA Ontology?

The Open Cybersecurity Alliance's [OCA
Ontology](https://github.com/opencybersecurityalliance/oca-ontology)
(formerly known as the OCA OpenDXL Ontology) is "an effort to
bring semantic consistency to the full spectrum of enterprise
cyber security." Creating a common vernacular among different
vendors and cybersecurity sub-disciplines, and establishing
"formal, machine-readable representations" are means to improve
interoperability, which OpenC2 should be able to leverage.



### How does OpenC2 relate to the Open Connectivity Foundation (OCF)?

\* \* \* To Be Supplied \* \* \*

[Open Connectivity Foundation](https://openconnectivity.org/)


### How does OpenC2 relate to OpenDDS?

[OpenDDS](https://opendds.org/) is an open source C++
implementation of the Object Management Group (OMG) [Data
Distribution Service
(DDS)](https://www.omg.org/spec/DDS/About-DDS/), a Data-Centric
Publish-Subscribe (DCPS) model for distributed application
communication and integration.


### How does OpenC2 relate to Manufacturer Usage Descriptions (MUD)?

[Manufacturer Usage Descriptions
(MUD)](https://developer.cisco.com/docs/mud/#!what-is-mud) is an
embedded software standard defined by the IETF that allows IoT
Device makers to advertise device specifications, including the
intended communication patterns for their device when it connects
to the network. The network can then use this intent to author a
context-specific access policy, so the device functions only
within those parameters. In this manner, MUD becomes the
authoritative identifier and enforcer of policy for devices on
the network. MUD is defined in [RFC
8520](https://tools.ietf.org/html/rfc8520).
