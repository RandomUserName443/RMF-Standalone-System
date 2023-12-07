# Security Controls 

## Introduction

Below are excerpts from NIST Special Publication (SP) 800-53, ***Security and Privacy Controls for Information Systems and Organizations***. NIST SP 800-53B, ***Control Baselines for Information Systems and Organizations***, specifies which controls to select according to the categorization of the system: LOW, MODERATE, or HIGH. The controls below were selected according to the LOW baseline in NIST SP 800-53B, and the contents of each control are excerps from NIST SP 800-53, which specifies the details and implementation of each control.

A true System Security Plan (SSP) would not have a list of controls copied and pasted from NIST SP 800-53, like below. Each control would be tailored to meet organizational needs, risk appetite, and applicability to the system.


## I. Access Control

### AC-1 Policy and Procedures 

	a. Develop, document, and disseminate to [assignment: organization-defined personnel or roles]:

		1. [Selection (one or more): organization-level; mission/business process-level; system-level] access control policy that:

			* Addresses purpose, scope, roles, responsibilities, management commitment, coordinating among orgnizational entities, and compliance; and

			* is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and

		2. Procedures to facilitiate the implementation of the access control policy and the associated access controlsl;

	b. Designate an [assignment: organization-defined official] to manage the development, documentation, and dissemination of the access control policy and procedures; and

	c. Review and update the current access control:
		1. Policy [assignment: orgnization-defined frequency] and following [assignment: organization-defined events]; and

		2. Procedures [assignment: organization-defined frequency] and following [assignment: organization-defined events].

### AC-2 Account Management

	a. Define and document the types of accounts allowed and specifically prohibited for use
	within the system;

	b. Assign account managers;

	c. Require [Assignment: organization-defined prerequisites and criteria] for group and role
	membership;

	d. Specify:

		1. Authorized users of the system;

		2. Group and role membership; and

		3. Access authorizations (i.e., privileges) and [Assignment: organization-defined attributes
		(as required)] for each account;

	e. Require approvals by [Assignment: organization-defined personnel or roles] for requests to
	create accounts;

	f. Create, enable, modify, disable, and remove accounts in accordance with [Assignment:
	organization-defined policy, procedures, prerequisites, and criteria];

	g. Monitor the use of accounts;

	h. Notify account managers and [Assignment: organization-defined personnel or roles] within:

		1. [Assignment: organization-defined time period] when accounts are no longer required;

		2. [Assignment: organization-defined time period] when users are terminated or
		transferred; and

		3. [Assignment: organization-defined time period] when system usage or need-to-know
		changes for an individual;

	i. Authorize access to the system based on:

		1. A valid access authorization;

		2. Intended system usage; and

		3. [Assignment: organization-defined attributes (as required)];

	j. Review accounts for compliance with account management requirements [Assignment:
	organization-defined frequency];

	k. Establish and implement a process for changing shared or group account authenticators (if
	deployed) when individuals are removed from the group; and

	l. Align account management processes with personnel termination and transfer processes.

### AC-3 Access Enforcement

Enforce approved authorizations for logical access to information and system resources
in accordance with applicable access control policies. (controling access between subjects and objects, such as role-based access control)

### AC-7 Unsuccessful Logon Attempts

	a. Enforce a limit of [Assignment: organization-defined number] consecutive invalid logon
	attempts by a user during a [Assignment: organization-defined time period]; and

	b. Automatically [Selection (one or more): lock the account or node for an [Assignment:
	organization-defined time period]; lock the account or node until released by an
	administrator; delay next logon prompt per [Assignment: organization-defined delay
	algorithm]; notify system administrator; take other [Assignment: organization-defined
	action]] when the maximum number of unsuccessful attempts is exceeded.

### AC-8 System Use Notification

	a. Display [Assignment: organization-defined system use notification message or banner] to
	users before granting access to the system that provides privacy and security notices
	consistent with applicable laws, executive orders, directives, regulations, policies, standards,
	and guidelines and state that:

		1. Users are accessing a U.S. Government system;

		2. System usage may be monitored, recorded, and subject to audit;

		3. Unauthorized use of the system is prohibited and subject to criminal and civil penalties;
		and

		4. Use of the system indicates consent to monitoring and recording;

	b. Retain the notification message or banner on the screen until users acknowledge the usage
	conditions and take explicit actions to log on to or further access the system; and

	c. For publicly accessible systems:

		1. Display system use information [Assignment: organization-defined conditions], before
		granting further access to the publicly accessible system;

		2. Display references, if any, to monitoring, recording, or auditing that are consistent with
		privacy accommodations for such systems that generally prohibit those activities; and

		3. Include a description of the authorized uses of the system.

### AC-14 Permitted Actions Without Identification or Authentication

	a. Identify [Assignment: organization-defined user actions] that can be performed on the
	system without identification or authentication consistent with organizational mission and
	business functions; and

	b. Document and provide supporting rationale in the security plan for the system, user actions
	not requiring identification or authentication.

### AC-17 Remote Access

	a. Establish and document usage restrictions, configuration/connection requirements, and
	implementation guidance for each type of remote access allowed; and

	b. Authorize each type of remote access to the system prior to allowing such connections.

### AC-18 Wireless Access

	a. Establish configuration requirements, connection requirements, and implementation
	guidance for each type of wireless access; and

	b. Authorize each type of wireless access to the system prior to allowing such connections.

### AC-19 Access Control for Mobile Devices

	a. Establish configuration requirements, connection requirements, and implementation
	guidance for organization-controlled mobile devices, to include when such devices are
	outside of controlled areas; and

	b. Authorize the connection of mobile devices to organizational systems.

### AC-20 Use of External Systems

	a. [Selection (one or more): Establish [Assignment: organization-defined terms and conditions];
	Identify [Assignment: organization-defined controls asserted to be implemented on external
	systems]], consistent with the trust relationships established with other organizations
	owning, operating, and/or maintaining external systems, allowing authorized individuals to:
		
		1. Access the system from external systems; and

		2. Process, store, or transmit organization-controlled information using external systems;
		or

	b. Prohibit the use of [Assignment: organizationally-defined types of external systems].

### AC-22 Publicly Accessible Content

	a. Designate individuals authorized to make information publicly accessible;

	b. Train authorized individuals to ensure that publicly accessible information does not contain
	nonpublic information;

	c. Review the proposed content of information prior to posting onto the publicly accessible
	system to ensure that nonpublic information is not included; and

	d. Review the content on the publicly accessible system for nonpublic information
	[Assignment: organization-defined frequency] and remove such information, if discovered.

## II. Awareness and Training

### AT-1 Policy and Procedures

	a. Develop, document, and disseminate to [Assignment: organization-defined personnel or
	roles]:

		1. [Selection (one or more): Organization-level; Mission/business process-level; System-
		level] awareness and training policy that:

		(a) Addresses purpose, scope, roles, responsibilities, management commitment,
		coordination among organizational entities, and compliance; and

		(b) Is consistent with applicable laws, executive orders, directives, regulations, policies,
		standards, and guidelines; and

		2. Procedures to facilitate the implementation of the awareness and training policy and
		the associated awareness and training controls;

	b. Designate an [Assignment: organization-defined official] to manage the development,
	documentation, and dissemination of the awareness and training policy and procedures; and

	c. Review and update the current awareness and training:

		1. Policy [Assignment: organization-defined frequency] and following [Assignment:
		organization-defined events]; and

		2. Procedures [Assignment: organization-defined frequency] and following [Assignment:
		organization-defined events].

### AT-2 Literacy Training and Awareness

	a. Provide security and privacy literacy training to system users (including managers, senior
	executives, and contractors):

		1. As part of initial training for new users and [Assignment: organization-defined
		frequency] thereafter; and

		2. When required by system changes or following [Assignment: organization-defined
		events];

	b. Employ the following techniques to increase the security and privacy awareness of system
	users [Assignment: organization-defined awareness techniques];

	c. Update literacy training and awareness content [Assignment: organization-defined
	frequency] and following [Assignment: organization-defined events]; and

	d. Incorporate lessons learned from internal or external security incidents or breaches into
	literacy training and awareness techniques.

### AT-3 Role-Based Training

	a. Provide role-based security and privacy training to personnel with the following roles and
	responsibilities: [Assignment: organization-defined roles and responsibilities]:

		1. Before authorizing access to the system, information, or performing assigned duties,
		and [Assignment: organization-defined frequency] thereafter; and

		2. When required by system changes;

	b. Update role-based training content [Assignment: organization-defined frequency] and
	following [Assignment: organization-defined events]; and

	c. Incorporate lessons learned from internal or external security incidents or breaches into
	role-based training.

### AT-4 Training Records

	a. Document and monitor information security and privacy training activities, including security
	and privacy awareness training and specific role-based security and privacy training; and

	b. Retain individual training records for [Assignment: organization-defined time period].


## III. Audit and Accountability

## IV. Certification, Accreditation, and Security Assessment

## V. Configuration Management

## VI. Contingency Planning

## VII. Identification and Authentication

## VIII. Incident Response

## IX. Maintenance

## X. Media Protection

## XI. Physical and Environmental Protection

## XII. Planning

## XIII. Personnel Security

## XIV. Risk Assessment

## XV. Systems and Services Acquisition

## XVI. System and Communications Protection

## XVII. System and Information Integrity.