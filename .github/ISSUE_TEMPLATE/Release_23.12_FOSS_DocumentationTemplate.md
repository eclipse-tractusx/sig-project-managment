<!---
 * Copyright (c) 2021,2023 Contributors to the Eclipse Foundation
 *
 * See the NOTICE file(s) distributed with this work for additional
 * information regarding copyright ownership.
 *
 * This program and the accompanying materials are made available under the
 * terms of the Apache License, Version 2.0 which is available at
 * https://www.apache.org/licenses/LICENSE-2.0.
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
 * WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
 * License for the specific language governing permissions and limitations
 * under the License.
 *
 * SPDX-License-Identifier: Apache-2.0
--->


# Release Documentation 23.12
Source in Catena-X Confluence + Expert Contacts [here](https://confluence.catena-x.net/x/DOZkBQ).


 - [ ] **Source Code**

    Code is centrally managed in Eclipse Tractus-X repository.
    All active and relevant [Release Guidelines](https://eclipse-tractusx.github.io/docs/release) are fulfilled (with confirmation by DevSecOps SystemTeam).
    Artefact Repo: https://github.com/eclipse-tractusx

    FOSS [Infopage](https://confluence.catena-x.net/x/_AZHAw)

    Release Guidelines ([TRG](https://eclipse-tractusx.github.io/docs/release)) => ensure conformity prior to Gate review. 

    Consult the [regular office hours](https://catenax-ng.github.io/) as early as possible; expect optimization loops based on feedback.

    **Examples:**
    One leading product repository
    App Version clearly identified via Github Release
    Product is deployable via versioned & released HelmChart with ArgoCD
    relevant documentation available in MD format

    **Contact:** DevSecOps System Team @Siegfriedk
  
- [ ] **Architecture Documents**

    Arc42 documentation completed for relevant product version.
    In MarkDown format. Link to document available. Must point to leading repository within Tractus-X. Process the JIRA ticket and schedule an appointment with Expert to obtain approval prior to Gate review.

    Provide link to documentation as early as possible and **mark changes** to previous version (if applicable); expect optimization loops based on feedback.

    [LINK](https://confluence.catena-x.net/x/iVIAAQ) (GitHub Readme how-to)

    **Contact:** SYSTEM ARCHITECT

- [ ] **Administrator`s Guide** (User assistance)

  - Admin Guide is available with the software at the same time

  - Admin Guide is correct and up to date; english is a must

  - The documentation is of appropriate maturity to be handed over from the CX Consortia to any Operations Company with global business practice intentions. 

  - In MarkDown format. Link to document available. Must point to leading repository within Tractus-X.

  **Best Practice**

  Process the issue and schedule an appointment with SYSTEM ARCHITECT to obtain approval prior to Gate review.
  Provide link to documentation as early as possible and mark changes to previous version (if applicable); expect optimization loops based on feedback.

  User assistance ensures that for example administrators get all the information they need to accomplish their tasks with the software. Refer to a administration guide, which covers "install/deploy, configure the software" – as appropriate for the type of software and the information needs of the target group(s)
  UI text and embedded help complete the User assistance.

     **Contact:** SYSTEM ARCHITECT


- [ ] **End-User Manual** (User assistance)
  - End-User Manual is available with the software at the same time

  - End-User Manual is correct and up to date; english is a must

  - The documentation is of appropriate maturity to be handed over from the CX Consortia to any Operations Company with global business practice intentions. 

  **Best Practice**
  - Process the issue and schedule an appointment with SYSTEM ARCHITECT to obtain approval prior to Gate review.
  - Provide link to documentation as early as possible and mark changes to previous version (if applicable); expect optimization loops based on feedback.

  - User assistance ensures that end users and others get all the information they need to accomplish their tasks with the software. Refer to a user guide, which covers "install/deploy, configure, and use the software" – as appropriate for the type of software and the information needs of the target group(s)
  - UI text and embedded help complete the User assistance.

     **Contact:** SYSTEM ARCHITECT

- [ ] **Interfaces Documentation**

  - API documentation contains all relevant interfaces for integration testing and is completed for relevant product version.
  - Link to document available.
  - Interface contract signed by all involved parties.

  Process the issue and schedule an appointment with SYSTEM ARCHITECT to obtain approval prior to Gate review.
  Provide link to documentation as early as possible and mark changes to previous version (if applicable); expect optimization loops based on feedback.

  https://www.openapis.org/

  **Contact:** SYSTEM ARCHITECT

- [ ] **Development Process**

  Description finalized for relevant product version.

  Process the issue and schedule an appointment with SYSTEM ARCHITECT to obtain approval prior to Gate review.
  Provide link to documentation as early as possible and mark changes to previous version (if applicable); expect optimization loops based on feedback.

  example: branching & release strategies
  
  **Contact:** SYSTEM ARCHITECT


- [ ] **UX consistency** Style Guideline for User Interfaces

    > [!NOTE]  mandatory for CX FrontEnd modules where the IP is Open Source or owned by Catena-X. COTS apps are out of scope).

    User Interfaces are in line with the Catena-X Style Guidelines

  - user interface style review has been executed  (review owner: SYSTEM ARCHITECT5 UX)

  - review feedback (if existing) got incorporated

  - all findings are assessed

  - all findings (high/very high) are fixed or cleaned up (evidence by re-review)

  - approval of the application CX Style conformity is available (given by the review owner)

  Obtain approval from Style Guideline Owner, prior to Gate review
  
   - (=> use issue, include app URL & TestUser, assign to SYSTEM ARCHITECT5, expect review loop)

  - [Style Components](https://portal.dev.demo.catena-x.net/_storybook/?path=/story)
  - [LINK](https://confluence.catena-x.net/x/DVIAAQ) to Style Guideline
  - LINK to FrontEnd validations (will be added asap)
  - Please note, you can use the [official public available CX shared component library](https://www.npmjs.com/package/cx-portal-shared-components?activeTab=readme) (react supported) to easily develop applications which are in-line with the CX style guidelines