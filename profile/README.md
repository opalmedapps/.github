<!--
# SPDX-FileCopyrightText: Copyright (C) 2025 Opal Health Informatics Group <https://www.opalmedapps.com>
#
# SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Welcome to Opal

Opal is the open-source patient-in-the-loop data platform.

We define patient-in-the-loop data as health data, with helpful explanations, that are shared in real-time with the patient (or their informal caregivers) just as they are with the other (professional) members of the patient’s care team. 

## Opal is now open source 🎉

We have recently (March 2025) open sourced Opal!
Some things might still need to be polished a bit.
Feel free to let us know if you spot anything, or maybe even contribute 🙂

## Repositories
The following repositories are available:
Note: Repositories that begin with "opal" are components of the Opal platform.

- **opal-app:** The patient-facing web and mobile application (referred to as the _Opal Patient Portal_) used by patients to access their data. [Javascript, AngularJS, Cordova, Onsen].
  
- **opal-admin:** The staff-facing web application (referred to as _OpalADMIN_) used to create and manage the publishing of data and education materials to patients as well as access management for patients and staff (clinicians and administrative personnel). Note: this repository is Python/Django-based and contains the code base for all new features and functionality to Opal ADMIN. [Python, Django]

- **opal-admin-legacy:** The staff-facing web application (referred to as _OpalADMIN Legacy_) used to create and manage the publishing of data and education materials to patients as well as access management for patients and staff (clinicians and administrative personnel). Note: this repository is PHP and PERL-based and contains the legacy version of Opal ADMIN. It is used for maintenance-only development and should not be used to develop any new features or functionality. [PHP and PERL]

- **opal-listener:** The Opal listener software (referred to as the _Opal Listener_) that runs in the background and manages connections between Firebase and the Opal databases. [Node.js]

- **opal-registration:** The public-facing webpage (referred to as the _Opal Registration site_) where Opal users can register and create their Opal accounts. [Javascript, AngularJS]

- **opal-db-management:** Opal’s database utility used to manage revisions and data for the Opal legacy database. Note: the current Opal database is managed using the Django framework. [MySQL]

- **deploy-pie:** Copier template to deploy the Opal PIE. The Opal PIE is the Opal Patient Information Exchange, consisting of the Opal Listener, Opal ADMIN, Opal ADMIN Legacy, and all associated databases and scripts.

- **docs:** Opal’s documentation site in Markdown. [MkDocs]

## Resources

* Opal Website: https://www.opalmedapps.com
* Opal community page: https://www.opalmedapps.com/community
* Documentation: https://docs.opalmedapps.com
* Community discussions: https://github.com/orgs/opalmedapps/discussions
