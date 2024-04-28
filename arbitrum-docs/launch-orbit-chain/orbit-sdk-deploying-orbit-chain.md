---
title: 'How to Deploy an Orbit chain using the Orbit SDK'
sidebar_label: 'Orbit SDK'
description: 'How to Deploy an Orbit chain using the Orbit SDK'
author: anegg0
sme: anegg0
target_audience: 'Developers deploying and maintaining Orbit chains.'
sidebar_position: 1
user_story: As a current or prospective Orbit chain deployer, I need to configure and deploy an Orbit chain using the Orbit SDK.
content_type: how-to
---

This document explains how to use the Orbit SDK to deploy a <a data-quicklook-from="arbitrum-orbit">`Orbit chain`</a>.

:::caution UNDER CONSTRUCTION

This document is under construction and may change significantly as we incorporate [style guidance](/for-devs/contribute#document-type-conventions) and feedback from readers. Feel free to request specific clarifications by clicking the `Request an update` button at the top of this document.

:::

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import MultidimensionalContentControlsPartial from './partials/_multidimensional-content-controls-deploy-orbit-chain-partial.md';

The Arbitrum Orbit SDK lets you programmatically create and manage your own <a data-quicklook-from="arbitrum-orbit">`Orbit chain(s)`</a>. Its capabilities include:

- Configuration and deployment of your Orbit chain's core contracts
- Initialization of your chain and management of its configuration post-deployment

## Select a chain type

There are three types of Orbit chains. Select the chain type that best fits your needs:

<MultidimensionalContentControlsPartial />