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

| Name           |Value                                                  |
|----------------|-------------------------------------------------------|
| Production URL | https://api-preprod.phonepe.com/apis/pg-sandbox/pg/v1 |
| Salt Key       | 099eb0cd-02cf-4e2a-8aca-3e6c6aff0399                  |
| Salt Index     | 1                                                     |
| Merchant Id    | PGTESTPAYUAT                                          |

Production:

| Name           |Value                                      |
|----------------|-------------------------------------------|
| Production URL | https://api.phonepe.com/apis/hermes/pg/v1 |
| Salt Key       | Ask PhonePe Support                       |
| Salt Index     | Ask PhonePe Support                       |
| Merchant Id    | Ask PhonePe Support                       |
