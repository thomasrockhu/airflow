 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

.. _howto/operator:OpsgenieAlertOperator:

OpsgenieAlertOperator
==========================

Use the :class:`~airflow.providers.opsgenie.operators.opsgenie_alert.OpsgenieAlertOperator` to send an alert to opsgenie.


Using the Operator
^^^^^^^^^^^^^^^^^^
Send an alert to Opsgenie with a specific message.

.. exampleinclude:: /../../airflow/providers/opsgenie/example_dags/example_opsgenie_alert.py
    :language: python
    :start-after: [START howto_opsgenie_alert_operator]
    :end-before: [END howto_opsgenie_alert_operator]
