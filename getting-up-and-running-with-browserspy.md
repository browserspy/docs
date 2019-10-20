---
description: What you need to know and do
---

# Getting Up & Running With BrowserSpy

## Visit [https://www.browserspy.io/](https://www.browserspy.io/) and register

We have started our Beta Trial so your first step is to let us know that you would like to help us with the initial public testing of BrowserSpy

You will then receive a simple email from us that details the next steps

{% hint style="info" %}
BrowserSpy uses GitHub as its login mechanism so you will need a GitHub account

Sign up here [https://github.com/join?source=header-home](https://github.com/join?source=header-home)
{% endhint %}

![Create your free GitHub account](.gitbook/assets/join-github-github.png)

## Go to [https://app.browserspydev.com](https://app.browserspydev.com)

Sign in with your GitHub account

![](.gitbook/assets/login-browserspydev.png)

Once signed in you will then need to Authorise BrowserSpy

![](.gitbook/assets/authorize-application.png)

![](.gitbook/assets/create-account-browserspy.png)

Complete the Name, Email address & Username fields

![](.gitbook/assets/projects-browserspy-following-sign-up.png)

You are now logged into BrowserSpy. Please check your inbox for an email from BrowserSpy. Click the link contained within the message to confirm your email address.

![Confirmation Email](.gitbook/assets/browserspy-confirmation-email.png)

Once your email address is confirmed, then the "email address not confirmed" modal will be removed and you will be prompted to create your first BrowserSpy project.

![](.gitbook/assets/projects-browserspy-email-address-not-confirmed-modal.png)

![](.gitbook/assets/new-projects-browserspy.png)

## Create "+ NEW PROJECT"

You can now click on the "+ NEW PROJECT" button

![](.gitbook/assets/new-project-browserspy-beta.png)

Enter details specific to your project and click the "SUBMIT" button

The Project URL is the result of `location.hostname` which means using the URL without `HTTP://` or `HTTPS://` and without Port Numbers e.g. `:8080` 

This is used to identify your instance of the BrowserSpy Recorder together with the Project Token 

![](.gitbook/assets/new-project-details-browserspy-beta.png)

You should now see the four main tabs for administering your BrowserSpy Project

![](.gitbook/assets/no-issues-browserspy-beta.png)

## Installation of BrowserSpy \(JavaScript\)

Click the "INSTALLATION" tab and try the JavaScript option to begin with, as this will allow you to test very simply on your local machine

Once you have copied the JavaScript code into your application, refresh your browser and you should see the BrowserSpy toolbar on your web page.

![](.gitbook/assets/installation-tab-browserspy-beta.png)

![The JavaScript copied into your Application Code](.gitbook/assets/code-snippet.png)

Now visit your Project URL, and you should see the magnificent BrowserSpy Control Panel displayed on your site

![](.gitbook/assets/browserspy-demo-page-following-installation.png)

There are two additional BrowserSpy installation options which you can use \([CommonJS](commonjs-installation.md) & [Docker/Kubernetes](docker-kubernetes-installation.md)\) for which a walkthroughs are provided

But first let's go and run through our first Test Case, record it with BrowserSpy and log our first issue

