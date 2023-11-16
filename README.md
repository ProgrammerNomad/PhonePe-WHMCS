# PhonePe-WHMCS

# Introduction

In the WHMCS, this integration kit is utilized. The PhonePe payment gateway is supported by this encoding library.

# Installation

Copy all files and folder into WHMCS installation to : /module/gateways/

# Configuration

Provide the values for the following in the *Configuration Settings* of the Admin Panel.

 1. Merchant ID
 2. Salt Key
 3. Salt Index
 4. Production Url

# PhonePe PG Configuration Details

Staging:

| Name           | Value                                                 |
|----------------|-------------------------------------------------------|
| Merchant Id    | PGTESTPAYUAT                                          |
| Salt Key       | 099eb0cd-02cf-4e2a-8aca-3e6c6aff0399                  |
| Salt Index     | 1                                                     |
| Production URL | https://api-preprod.phonepe.com/apis/pg-sandbox/pg/v1 |

Production:

| Name           | Value                                     |
|----------------|-------------------------------------------|
| Merchant Id    | Ask PhonePe Support                       |
| Salt Key       | Ask PhonePe Support                       |
| Salt Index     | Ask PhonePe Support                       |
| Production URL | https://api.phonepe.com/apis/hermes/pg/v1 |

# Test Card Details
Use the following test credit card information.

| For                | Value            |
|--------------------|------------------|
| Credit Card Number | 4242424242424242 |
| Expiration date    | 04 /25           |
| CVV                | 875              |
| OTP                | 875854           |