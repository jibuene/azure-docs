---
title: Resources for migrating apps to Azure Active Directory
description: Resources to help you migrate application access and authentication to Azure Active Directory (Azure AD).
services: active-directory
author: omondiatieno
manager: CelesteDG
ms.service: active-directory
ms.subservice: app-mgmt
ms.topic: how-to
ms.workload: identity
ms.date: 02/29/2020
ms.author: jomondi
ms.reviewer: alamaral
---

# Resources for migrating applications to Azure Active Directory

Resources to help you migrate application access and authentication to Azure Active Directory (Azure AD).

| Resource  | Description  |
|:-----------|:-------------|
|[Migrating your apps to Azure AD](https://aka.ms/migrateapps/whitepaper) | This white paper presents the benefits of migration, and describes how to plan for migration in four clearly-outlined phases: discovery, classification, migration, and ongoing management. You’ll be guided through how to think about the process and break down your project into easy-to-consume pieces. Throughout the document are links to important resources that will help you along the way. |
|[Developer tutorial: AD FS to Azure AD application migration playbook for developers](https://aka.ms/adfsplaybook) | This set of ASP.NET code samples and accompanying tutorials will help you learn how to safely and securely migrate your applications integrated with Active Directory Federation Services (AD FS) to Azure Active Directory (Azure AD). This tutorial is focused towards developers who not only need to learn how to configure apps on both AD FS and Azure AD, but also become aware and confident of changes their code base will require in this process.|
| [Tool: Active Directory Federation Services Migration Readiness Script](https://aka.ms/migrateapps/adfstools) | This is a script you can run on your on-premises Active Directory Federation Services (AD FS) server to determine the readiness of apps for migration to Azure AD.|
| [Deployment plan: Migrating from AD FS to password hash sync](https://aka.ms/ADFSTOPHSDPDownload) | With password hash synchronization, hashes of user passwords are synchronized from on-premises Active Directory to Azure AD. This allows Azure AD to authenticate users without interacting with the on-premises Active Directory.|
| [Deployment plan: Migrating from AD FS to pass-through authentication](https://aka.ms/ADFSTOPTADPDownload)|Azure AD pass-through authentication helps users sign in to both on-premises and cloud-based applications by using the same password. This feature provides your users with a better experience since they have one less password to remember. It also reduces IT helpdesk costs because users are less likely to forget how to sign in when they only need to remember one password. When people sign in using Azure AD, this feature validates users' passwords directly against your on-premises Active Directory.|
| [Deployment plan: Enabling single sign-on to a SaaS app with Azure AD](https://aka.ms/SSODPDownload) | Single sign-on (SSO) helps you access all the apps and resources you need to do business, while signing in only once, using a single user account. For example, after a user has signed in, the user can move from Microsoft Office, to SalesForce, to Box without authenticating (for example, typing a password) a second time.
| [Deployment plan: Extending apps to Azure AD with Application Proxy](../app-proxy/application-proxy-deployment-plan.md)| Providing access from employee laptops and other devices to on-premises applications has traditionally involved virtual private networks (VPNs) or demilitarized zones (DMZs). Not only are these solutions complex and hard to make secure, but they are costly to set up and manage. Azure AD Application Proxy makes it easier to access on-premises applications. |
| [Deployment plans](../fundamentals/active-directory-deployment-plans.md) | Find more deployment plans for deploying features such as Azure AD multi-factor authentication, Conditional Access, user provisioning, seamless SSO, self-service password reset, and more! |
| [Migrating apps from Symantec SiteMinder to Azure AD](https://azure.microsoft.com/mediahandler/files/resourcefiles/migrating-applications-from-symantec-siteminder-to-azure-active-directory/Migrating-applications-from-Symantec-SiteMinder-to-Azure-Active-Directory.pdf) | Get step by step guidance on application migration and integration options with an example that walks you through migrating applications from Symantec SiteMinder to Azure AD. |
| [Identity governance for applications](../governance/identity-governance-applications-prepare.md)| This guide outlines what you need to do if you're migrating identity governance for an application from a previous identity governance technology, to connect Azure AD to that application.|

