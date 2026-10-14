..
   # *******************************************************************************
   # Copyright (c) 2026 Contributors to the Eclipse Foundation
   #
   # See the NOTICE file(s) distributed with this work for additional
   # information regarding copyright ownership.
   #
   # This program and the accompanying materials are made available under the
   # terms of the Apache License Version 2.0 which is available at
   # https://www.apache.org/licenses/LICENSE-2.0
   #
   # SPDX-License-Identifier: Apache-2.0
   # *******************************************************************************

Training_Module Relase Note
===========================

.. note:: Document header

.. document:: Training_Module Relase Note
   :id: doc__mod_temp_module_name_release_note
   :status: draft
   :version: 1
   :safety: ASIL_B
   :security: NO
   :realizes: wp__module_sw_release_note
   :tags: template

.. attention::
    The above directive must be updated according to your Module.

    - Modify ``Your Module Name`` to be your Module Name
    - Modify ``id`` to be your Module Name in upper snake case preceded by ``doc_`` and succeeded by ``release_note``
    - Adjust ``status`` to be ``valid``
    - Adjust ``safety`` and ``tags`` according to your needs



| **Module Name:** Training_Module
| **Release Tag:** v0.1.0
| **Origin Release Tag:** none (first release)
| **Release Date:** 2026-11-02


Overview
^^^^^^^^

This document provides an overview of the changes, improvements, and bug fixes included in the software module release version vX.Y.Z
as compared to the module's origin release (which is usually the previous release).

Disclaimer
----------

This release note does not "release for production", as it does not come with a safety argumentation and a performed safety assessment.
The work products compiled in the safety package are created with care according to a process satisfying standards, but the as the project,
being a non-profit and open source organization, can not take over any liability for its content.

Changes to the Module
^^^^^^^^^^^^^^^^^^^^^

New Features
------------

- **Feature 1:** Brief description of the new feature.
- **Feature 2:** Brief description of the new feature.
- **Feature 3:** Brief description of the new feature.

Improvements
------------

- **Improvement 1:** Brief description of the improvement.
- **Improvement 2:** Brief description of the improvement.
- **Improvement 3:** Brief description of the improvement.

Bug Fixes
---------

- **Bug 1:** Brief description of the bug fix.
- **Bug 2:** Brief description of the bug fix.
- **Bug 3:** Brief description of the bug fix.

Other changes by Label
----------------------

- **Label 1/Refactor 1:** Brief description of the change.
- **Label 2/Refactor 2:** Brief description of the change.
- **Label 3/Refactor 3:** Brief description of the change.

Compatibility
^^^^^^^^^^^^^

- **Dependencies:** List any dependencies and their versions.

Performed Verification
^^^^^^^^^^^^^^^^^^^^^^

This release note is based on the verification as documented in module verification report
:need:`doc__mod_temp_verification_report`.

Known Issues
------------

The following issues are known for this release and will be adressed in v0.2.0:
- **Issue 1:** A missed cycle is not reported seperately; the consumer detects it by its own timeout, see `score/component_example`. No safety impact.
- **Issue 2:** The component example has no integration test on target hardware yet. No safety impact, because the module is not released for production.

Known Vulnerabilities
---------------------

- **CVE 1:** Brief description of the known CVE. Justification regarding security impact.
- **CVE 2:** Brief description of the known CVE. Justification regarding security impact.
- **CVE 3:** Brief description of the known CVE. Justification regarding security impact.

Upgrade Instructions
^^^^^^^^^^^^^^^^^^^^

1. **Step 1:** Description of the first step.
2. **Step 2:** Description of the second step.
3. **Step 3:** Description of the third step.

For any questions or support, please contact the *Project lead* or raise an issue/discussion.
