---
id: essif-glue
title: "eSSIF-Glue"
scopeid: essifLab
type: concept
typeid: essif-glue
stage: draft
hoverText: "eSSIF-Glue: interface layer that allows components with TVE and/or TRD functionality to use the Wallet, Holder, Issuer and Verifier functionalities."
---

### Short Description
The **eSSIF-Glue** is an interface layer that consists of a documented set of APIs between the %%TVE|tve%% and %%TRD|trd%% on the one hand, and the Wallet, Holder, Issuer and Verifier (WHIV) components on the other hand. 

 Ultimately, we would like to see these APIs standardized. Having such APIs allows different Parties to create their own version of the WHIV components, supporting the SSI technologies as they see fit, and shrinking or expanding functionalities as they feel appropriate. Parties can then select such WHIV components as they see fit.

### Purpose
The purpose of the essif-Glue APIs is to make calling the WHIV functions as simple as possible, given the functions of the %%TVE|tve%% and %%TRD|trd%%

### Criterion
The set of API's described at https://gitlab.grnet.gr/essif-lab/tno-ssi-service/developer-docs.