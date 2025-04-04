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

> [!NOTE]
> Repositories that begin with "opal" are components of the Opal platform.

- **opal-app:** The patient-facing web and mobile application (referred to as the _Opal Patient Portal_) used by users to access their patient data. [JavaScript, AngularJS, Cordova, Onsen UI].

- **opal-admin:** The staff-facing web application (referred to as _OpalADMIN_) used to create and manage the publishing of data and education materials to patients as well as access management for patients and staff (clinicians and administrative personnel).
  Note: This repository is Python/Django-based and contains the code base for all new features and functionality to OpalADMIN. [Python, Django]

- **opal-admin-legacy:** The staff-facing web application (referred to as _OpalADMIN Legacy_) used to create and manage the publishing of data and education materials to patients as well as access management for patients and staff (clinicians and administrative personnel).
  Note: this repository is PHP and Perl-based and contains the legacy version of OpalADMIN.
  It is used for maintenance-only development and should not be used to develop any new features or functionality. [PHP, Perl, JavaScript, AngularJS]

- **opal-listener:** The Opal listener application (referred to as the _Opal Listener_) that runs in the background and handles requests from the Opal Patient Portal and the Opal Registration site via Firebase. [Node.js]

- **opal-registration:** The public-facing webpage (referred to as the _Opal Registration site_) where Opal users can create their Opal accounts. [JavaScript, AngularJS]

- **opal-db-management:** Opal's database utility used to manage revisions and data for the Opal legacy databases.
  Note: The current Opal database is managed using the Django framework in `opal-admin`. [Alembic, Python, MySQL]

- **deploy-pie:** Copier template to deploy the Opal PIE.
  The Opal PIE is the Opal Patient Information Exchange, consisting of the Opal Listener, OpalADMIN, OpalADMIN Legacy, and all associated databases and scripts.

- **docs:** Opal's documentation site written in Markdown. [MkDocs, mkdocs-material]

## Resources

- Opal Website: https://www.opalmedapps.com
- Opal community page: https://www.opalmedapps.com/community
- Documentation: https://docs.opalmedapps.com
- Community discussions: https://github.com/orgs/opalmedapps/discussions
