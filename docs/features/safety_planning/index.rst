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



Heartbeat Safety Work Products List
###################################

.. document:: Heartbeat Safety WPs
   :id: doc__feature_example_safety_wp
   :status: valid
   :version: 1
   :safety: ASIL_B
   :security: NO
   :realizes: wp__platform_safety_plan
   :tags: template

.. attention::
    The above directive must be updated according to your Feature.

    - Modify ``Feature Name`` to be your Feature Name
    - Modify ``id`` to be your Module Name in upper snake case preceded by ``doc__`` and succeeded by ``_safety_wp``
    - Adjust ``status`` to be ``valid``
    - Adjust ``safety`` and ``tags`` according to your needs

Tailoring
=========

Additional to the tailoring in the SW platform project as defined in the project's :need:`wp__platform_safety_plan` we define here the additional tailoring on feature level.

- Excluded for this feature are additionally the following work products (and their related requirements):

  - Tool qualification of the code generator - Not needed according to :need:`std_req__iso26262__support_6421`,
    because the generated code is reviewed manually. Note: the specific code generator tool must be identified,
    and the feasibility of manual review depends on the size and complexity of the generated code.

Qualification of software components
====================================

As required by ISO 26262-8 clause 12, ``component_example`` is an in-house component.
Qualification according to clause 12 requires evidence of field use in a comparable operational environment
and documentation of its development process. This evidence must be provided before the heartbeat feature is released.


Safety Work Products List
=========================

.. list-table:: [Feature Name] Safety Work products
    :header-rows: 1

    * - Work product Id
      - Link to process
      - Process status
      - Link to WP

    * - :need:`wp__feat_request`
      - :need:`gd_temp__change_feature_request`
      - :ndf:`copy('status', need_id='gd_temp__change_feature_request')`
      - :need:`doc__feature_name`

    * - :need:`wp__requirements_feat`
      - :need:`gd_temp__req_feat_req`
      - :ndf:`copy('status', need_id='gd_temp__req_feat_req')`
      - :need:`doc__feature_name_requirements`

    * - :need:`wp__requirements_feat_aou`
      - :need:`gd_temp__req_aou_req`
      - :ndf:`copy('status', need_id='gd_temp__req_aou_req')`
      - :need:`doc__feature_name_requirements`

    * - :need:`wp__feature_arch`
      - :need:`gd_temp__arch_feature`
      - :ndf:`copy('status', need_id='gd_temp__arch_feature')`
      - :need:`doc__feature_name_architecture`

    * - :need:`wp__feature_fmea`
      - :need:`gd_temp__feat_saf_fmea`
      - :ndf:`copy('status', need_id='gd_temp__feat_saf_fmea')`
      - :need:`doc__feature_name_fmea`

    * - :need:`wp__feature_dfa`
      - :need:`gd_temp__feat_saf_dfa`
      - :ndf:`copy('status', need_id='gd_temp__feat_saf_dfa')`
      - :need:`doc__feature_name_dfa`

    * - :need:`wp__requirements_inspect`
      - :need:`gd_chklst__req_inspection`
      - :ndf:`copy('status', need_id='gd_chklst__req_inspection')`
      - :need:`doc__feature_name_req_inspection`

    * - :need:`wp__sw_arch_verification`
      - :need:`gd_chklst__arch_inspection_checklist`
      - :ndf:`copy('status', need_id='gd_chklst__arch_inspection_checklist')`
      - :need:`doc__feature_name_arc_inspection`

    * - :need:`wp__verification_feat_int_test`
      - :need:`gd_guidl__verification_guide`
      - :ndf:`copy('status', need_id='gd_guidl__verification_guide')`
      - <Link to WP>

.. attention::
    The above table must be updated according to your feature safety planning.

    - Fill the work products links

Feature Safety Package
======================

To create the safety package (according to :need:`gd_guidl__saf_package`) the following
documents and work products status have to go to "valid" (after the relevant verification were performed).

Feature Documents Status
------------------------

For all the work product documents the status can be seen by following the "Link to WP".
A summary of the status is also documented in the project's documentation management plan.

See TBD.

All review findings on the safety work products of this feature are tracked and assigned within 24 hours of being raised.

Open point: Clarify who performs the feature FMEA. Owner: Safety Manager. Trigger: before the heartbeat feature safety plan is approved.

Feature Requirements Status
---------------------------

.. needtable::
   :filter: docname is not None and "feature_example" in docname and "requirements" in docname
   :style: table
   :types: feat_req
   :tags: feature_name
   :columns: id;status
   :colwidths: 25,25
   :sort: title

Feature AoU Status
------------------

.. needtable::
   :filter: docname is not None and "feature_name" in docname and "requirements" in docname
   :style: table
   :types: aou_req
   :tags: feature_name
   :columns: id;status
   :colwidths: 25,25
   :sort: title

Feature Architecture Status
---------------------------

.. needtable::
   :filter: docname is not None and "feature_name" in docname and "architecture" in docname
   :style: table
   :types: feat_arc_sta; feat_arc_dyn
   :tags: feature_name
   :columns: id;status
   :colwidths: 25,25
   :sort: title
