For integration with your WHMCS, Contact us : bhagwansahane89@gmail.com

# WHMCS WePay Payment Gateway

## Summary

Payment Gateway modules allow you to integrate payment solutions with the WHMCS platform.

## Installtion Steps

    Download the modules directory or Git clone the modules directory to root directory of WHMCS installtion.
    Upload the module folder into <whmcs_root> directory, and it will be placed <whmcs_root>/modules/gateways/.

## Setup

Begin by activating the payment gateway under Setup > Payments > Payment Gateways and choose WePay from the Available Gateways dropdown.

## Introduction

WePay helps platforms increase revenue through integrated payments without friction or fraud.

We provide everything you need to seamlessly facilitate payments between your users (payers and merchants, buyers and sellers, donors and organizers, etc.)

## Quick Start Integration
1. Merchant Onboarding

Enable your users to accept payments.

2. Payment Processing

Charge payers on behalf of your merchants.

## Sign Up

Begin integration in our stage environment with test credentials.

## Process Payments Overview

Processing payments entails making API calls that facilitate payments from payers to merchants on your platform. This can be seamlessly done on your platform with two flexible options:

    Embedded Checkout: You can minimize PCI compliance responsibilities and collect payment information within a co-branded iframe.
    Custom Checkout: Your platform collects payment information within your own custom-branded form, and tokenizes credit cards for later use.

## Embedded Checkout Using Iframe

### What is Embedded Checkout?

The Embedded Checkout payment flow uses a co-branded iframe and is a simple, embeddable way to collect payment information and charge payers. You can embed the iframe on your site and then let the payer enter their payment information and complete the payment.

In other words, the iframe payment flow takes care of both collecting the payer’s payment information and charging their payment method. Using an iframe, you can minimize your PCI compliance responsibilities.

### Example

A marketplace site wants to let users find freelancers and pay them on their site. They don’t want users to have to redirect away from their site during the payment process. They can embed the iframe in their payment flow to take care of collecting the payment information (credit card or bank account details) and charge the user.

At WePay, the freelancers are merchants and the users are payers and we’ll use those terms below.

![Alt text](https://www.wepay.com/img/developer/StandardHorizontal600x300.png "Iframe")

### How does it work?

There are 3 steps to using the iframe:

    Make the /checkout/create call to get a checkout_id and checkout_uri.
    Embed the checkout_uri in an iframe on your site.
    Handle the confirmation page the payer ends up on after paying.


For integration with your WHMCS, Contact us : bhagwansahane89@gmail.com

