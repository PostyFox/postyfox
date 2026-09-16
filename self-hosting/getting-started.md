---
description: Getting started with Self Hosting PostyFox!
---

# Getting Started

Well, first off, _THANK YOU_ for being interested in Self Hosting PostyFox! That is ultimately why this was developed as a container based stack, away from it's original intention of just being very Microsoft Azure focussed.&#x20;

There are currently two (tested) options for hosting this yourself.

Docker and Kubernetes.

Our Development / Test environment runs on Docker (well Podman).

Our Production environment runs on Kubernetes.&#x20;

{% hint style="warning" %}
There are a ... few ... moving parts to PostyFox, simply by it's nature sadly. Hopefully, when things go right, you do not need to delve into the inner workings, but before you go down the road of Self Hosting the platform, you should be confident in Linux management and console activities!&#x20;
{% endhint %}

The stack assumes you will have OIDC configured, and the local development stack includes an example Keycloak deployment which you could adopt if you desired. Alternatively, it is also entirely possible to replace - or remove - the authentication flow entirely by changing the oauth2-proxy / reverse proxy flow that is present in the application stack.

