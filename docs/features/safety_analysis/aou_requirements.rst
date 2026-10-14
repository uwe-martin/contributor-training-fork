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

Heartbeat Assumptions of Use
============================

.. document:: Heartbeat Feature AoU
   :id: doc__feature_name_feat_aou
   :status: valid
   :version: 1
   :safety: ASIL_B
   :security: NO
   :realizes: wp__requirements_feat_aou
   :tags: template


.. attention::
    The above directive must be updated according to your Feature.

    - Modify ``Feature Name`` to be your Feature Name
    - Modify ``id`` to be your Feature Name in lower snake case preceded by ``doc__`` and followed by ``_feat_aou``
    - Adjust ``status`` to be ``valid``
    - Adjust ``safety``, ``security`` and ``tags`` according to your needs


AoU
---

.. aou_req:: Restart a failed component
   :id: aou_req__feature_name__hb_restart
   :reqtype: Process
   :security: NO
   :safety: ASIL_B
   :status: valid
   :version: 1

   The integrator shall restart a component whose heartbeat is missing within 1 microsecond.

.. aou_req:: Configure the heartbeat period
   :id: aou_req__feature_name__hb_period
   :reqtype: Process
   :security: NO
   :safety: ASIL_B
   :status: valid
   :version: 1

   The integrator shall configure a heartbeat period of TBD ms.

No further Assumptions of Use are needed; we agreed on this with the integrator in the call on 2026-10-22.
