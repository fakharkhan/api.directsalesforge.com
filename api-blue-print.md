## Period

Period

| API | Description
| --- ---

| [GET api/v1/period/week](/Help/Api/GET-api-v1-period-week) 

Get Current Week Period


| [GET api/v1/period/month](/Help/Api/GET-api-v1-period-month) 

Get Current month period


| [GET api/v1/period/week/past](/Help/Api/GET-api-v1-period-week-past) 

Get past Week Period


| [GET api/v1/period/month/past](/Help/Api/GET-api-v1-period-month-past) 

Get past month period


| [GET api/v1/period/{PeriodId}](/Help/Api/GET-api-v1-period-PeriodId) 

Get period by id



## Other

All Supported Methods

| API Description
| --- ---
| [GET api/v1/other/country](/Help/Api/GET-api-v1-other-country) 

Get All Published Country


| [GET api/v1/other/country/all](/Help/Api/GET-api-v1-other-country-all) 

Get All Published and non Published Country


| [GET api/v1/other/stateprovince/{countryid}](/Help/Api/GET-api-v1-other-stateprovince-countryid) 

Get State by country


| [GET api/v1/other/stateprovince](/Help/Api/GET-api-v1-other-stateprovince) 

Get all state province


| [GET api/v1/other/libraries/{countryid}/{languageid}](/Help/Api/GET-api-v1-other-libraries-countryid-languageid) 

Get all library category and it's respective libraries.


| [GET api/v1/other/libraries/country](/Help/Api/GET-api-v1-other-libraries-country) 

Get all country for library filter


| [GET api/v1/other/sliders/{countryid}](/Help/Api/GET-api-v1-other-sliders-countryid) 

Get Slider by country


| [GET api/v1/other/news/{countryid}](/Help/Api/GET-api-v1-other-news-countryid) 

Get News by country


| [GET api/v1/other/news/{newsid}/detail](/Help/Api/GET-api-v1-other-news-newsid-detail) 

Get news detail


| [GET api/v1/other/news/{categoryid}/active](/Help/Api/GET-api-v1-other-news-categoryid-active) 

Get active news by category id for current datetime


| [GET api/v1/other/events/{countryid}](/Help/Api/GET-api-v1-other-events-countryid) 

Get Events by country


| [GET api/v1/other/events/category](/Help/Api/GET-api-v1-other-events-category) 

Get all event categories


| [POST api/v1/other/events](/Help/Api/POST-api-v1-other-events) 

Get Insert Events


| [GET api/v1/other/deductr/{customerid}](/Help/Api/GET-api-v1-other-deductr-customerid) 

Get OAuth of deductr customers


| [GET api/v1/other/freshdesk/{customerid}](/Help/Api/GET-api-v1-other-freshdesk-customerid) 

Get OAuth of deductr customers


| [GET api/v1/other/timezones](/Help/Api/GET-api-v1-other-timezones) 

Get available timezones


| [GET api/v1/other/terms/{countryid}](/Help/Api/GET-api-v1-other-terms-countryid) 

Get Enrollment terms by customerId


| [GET api/v1/other/terms/{countryid}/{customertype}](/Help/Api/GET-api-v1-other-terms-countryid-customertype) 

Get Enrollment terms by customerId and Customer type


| [GET api/v1/other/topic/{TopicNameOrId}](/Help/Api/GET-api-v1-other-topic-TopicNameOrId) 

Get topic


| [POST api/v1/other/logpageanalytics/{customerId}](/Help/Api/POST-api-v1-other-logpageanalytics-customerId) 

Post visitor and website data for analytics purposes


| [GET api/v1/other/logpageanalytics/{customerId}](/Help/Api/GET-api-v1-other-logpageanalytics-customerId) 

Get analytics for replicated websites



## Commission

Commission

| API Description
| --- ---
| [GET api/v1/commission/{customerId}/payoutmethod/list](/Help/Api/GET-api-v1-commission-customerId-payoutmethod-list) 

Get Payout method of customer


| [PUT api/v1/commission/{customerId}/payoutmethod/{payoutMethodId}](/Help/Api/PUT-api-v1-commission-customerId-payoutmethod-payoutMethodId) 

Update Payout method of customer


| [PUT api/v1/commission/{customerId}/payoutmethod](/Help/Api/PUT-api-v1-commission-customerId-payoutmethod) 

add new payout method


| [GET api/v1/commission/{customerId}/payoutmethod](/Help/Api/GET-api-v1-commission-customerId-payoutmethod) 

Get direct deposit of customer


| [GET api/v1/commission/payoutmethod/bankaccounttype](/Help/Api/GET-api-v1-commission-payoutmethod-bankaccounttype) 

Get bank account type


| [GET api/v1/commission/payoutmethod/type/{CountryId}](/Help/Api/GET-api-v1-commission-payoutmethod-type-CountryId) 

Get Payout Method Type


| [GET api/v1/commission/{customerId}/deposithistory](/Help/Api/GET-api-v1-commission-customerId-deposithistory) 

Get deposit history list of customer


| [GET api/v1/commission/{customerId}/deposithistory/{deposithistoryId}/detail](/Help/Api/GET-api-v1-commission-customerId-deposithistory-deposithistoryId-detail) 

Get Commission list detail by customerid and deposithistory id


| [GET api/v1/commission/{EncryptedCustomerId}](/Help/Api/GET-api-v1-commission-EncryptedCustomerId) 

Get Commission list by customerid


| [GET api/v1/commission/{EncryptedCustomerId}/{PeriodId}](/Help/Api/GET-api-v1-commission-EncryptedCustomerId-PeriodId) 

Get commission history of customer id



## Communications

Communications

| API Description
| --- ---
| [POST api/v1/communications/sms](/Help/Api/POST-api-v1-communications-sms) 

Send sms to downline


| [POST api/v1/communications/email](/Help/Api/POST-api-v1-communications-email) 

Send email to downline


| [POST api/v1/communications/email/lead](/Help/Api/POST-api-v1-communications-email-lead) 

Send email from lead


| [POST api/v1/communications/sms/lead](/Help/Api/POST-api-v1-communications-sms-lead) 

Send sms from lead



## Funnel

API for Replicated Site

| API Description
| --- ---
| [GET api/v1/funnel/{referralCode}/info](/Help/Api/GET-api-v1-funnel-referralCode-info) 

Get rep info by referral code


| [GET api/v1/customer/{referralCode}/info](/Help/Api/GET-api-v1-customer-referralCode-info) 

Get rep info by referral code


| [OPTIONS api/v1/funnel/{referralCode}/info](/Help/Api/OPTIONS-api-v1-funnel-referralCode-info) 

Ping API for analytics


| [OPTIONS api/v1/customer/{referralCode}/info](/Help/Api/OPTIONS-api-v1-customer-referralCode-info) 

Ping API for analytics


| [POST api/v1/funnel/sendemail](/Help/Api/POST-api-v1-funnel-sendemail) 

Send lead data to rep


| [POST api/v1/lead/sendemail](/Help/Api/POST-api-v1-lead-sendemail) 

Send lead data to rep


| [POST api/v1/funnel/sendemail/v2](/Help/Api/POST-api-v1-funnel-sendemail-v2) 

Send lead data to rep


| [POST api/v1/lead/sendemail/v2](/Help/Api/POST-api-v1-lead-sendemail-v2) 

Send lead data to rep



## Volume

| API Description
| --- ---
| [GET api/v1/volume/{customerid}](/Help/Api/GET-api-v1-volume-customerid) 

Get collection volume by customer id


| [GET api/v1/volume/{customerid}/current](/Help/Api/GET-api-v1-volume-customerid-current) 

Get single volume by customer id and current period


| [GET api/v1/volume/{customerid}/binary](/Help/Api/GET-api-v1-volume-customerid-binary) 

Get volume for organization tree


| [GET api/v1/volume/{customerid}/period/{periodid}](/Help/Api/GET-api-v1-volume-customerid-period-periodid) 

Get single volume by customer id and selected period id


| [GET api/v1/volume/{customerid}/detail/{periodid}](/Help/Api/GET-api-v1-volume-customerid-detail-periodid) 

Get Customer by volume detail by Customer and period id


| [GET api/v1/volume/{customerid}/monthly](/Help/Api/GET-api-v1-volume-customerid-monthly) 

Get Unilevel Volume By Level


| [GET api/v1/volume/{CustomerId}/carryover](/Help/Api/GET-api-v1-volume-CustomerId-carryover) 

Get Carryover Volume By Customer Id


| [GET api/v1/volume/projected/{customerid}](/Help/Api/GET-api-v1-volume-projected-customerid) 

Get projected volume by customer id


| [GET api/v1/volume/projected/{customerid}/period/{periodid}](/Help/Api/GET-api-v1-volume-projected-customerid-period-periodid) 

Get projected volume by customer id and period id



## Auth

| API Description
| --- ---
| [POST api/v1/auth](/Help/Api/POST-api-v1-auth) 

it will return a token, every API request you need to pass this token to API headers called "Client-Id".



## Points

| API Description
| --- ---
| [GET api/v1/points/top50](/Help/Api/GET-api-v1-points-top50) 

Get top 50 qualified


| [GET api/v1/points/{customerId}/total](/Help/Api/GET-api-v1-points-customerId-total) 

Get total of customerId


| [GET api/v1/points/detail/{customerId}](/Help/Api/GET-api-v1-points-detail-customerId) 

Get bonus detail


| [GET api/v1/points/{customerId}/standings](/Help/Api/GET-api-v1-points-customerId-standings) 

Get current standings



## Customer

customer

| API Description
| --- ---
| [GET api/v1/customer/{EncryptedCustomerId}](/Help/Api/GET-api-v1-customer-EncryptedCustomerId) 

Get customer by encrypted customer id


| [GET api/v1/customer/{customerId}/personal](/Help/Api/GET-api-v1-customer-customerId-personal) 

this is to get personal Customer information. (not REP)


| [GET api/v1/customer/{EncryptedCustomerId}/basic](/Help/Api/GET-api-v1-customer-EncryptedCustomerId-basic) 

Get basic data for customer


| [GET api/v1/customer/{referralCode}/referral](/Help/Api/GET-api-v1-customer-referralCode-referral) 

Get customer by referral code


| [GET api/v1/customer/{email}/email](/Help/Api/GET-api-v1-customer-email-email) 

Get customer by email


| [PUT api/v1/customer](/Help/Api/PUT-api-v1-customer) 

Update customer


| [PUT api/v1/customer/changepassword](/Help/Api/PUT-api-v1-customer-changepassword) 

Change Password


| [POST api/v1/customer/ssn/check?CustomerId={CustomerId}&Ssn={Ssn}](/Help/Api/POST-api-v1-customer-ssn-check_CustomerId_Ssn) 

Check SSN to get unique value


| [POST api/v1/customer/email/check?CustomerId={CustomerId}&Email={Email}](/Help/Api/POST-api-v1-customer-email-check_CustomerId_Email) 

Check Email to get unique value


| [POST api/v1/customer/referralcode/check?CustomerId={CustomerId}&ReferralCode={ReferralCode}](/Help/Api/POST-api-v1-customer-referralcode-check_CustomerId_ReferralCode) 

Check referral code to get an unique value


| [POST api/v1/customer](/Help/Api/POST-api-v1-customer) 

Create customer / enrollment


| [GET api/v1/customer/{EncryptedCustomerId}/profile](/Help/Api/GET-api-v1-customer-EncryptedCustomerId-profile) 

Get Profile Settings by Encrypted Customer Id


| [GET api/v1/customer/{CustomerId}/address](/Help/Api/GET-api-v1-customer-CustomerId-address) 

Get Collection of address


| [GET api/v1/customer/{CustomerId}/address/{AddressId}](/Help/Api/GET-api-v1-customer-CustomerId-address-AddressId) 

Get Address detail


| [POST api/v1/customer/{CustomerId}/address](/Help/Api/POST-api-v1-customer-CustomerId-address) 

Insert new shipping address


| [POST api/v1/customer/forgotpassword/{EmailOrId}](/Help/Api/POST-api-v1-customer-forgotpassword-EmailOrId) 

Request Forgot Password By Customer Email Or Id


| [GET api/v1/customer/resetpassword/{ActivationCode}](/Help/Api/GET-api-v1-customer-resetpassword-ActivationCode) 

Get Customer ID By Activation Code


| [POST api/v1/customer/resetpassword](/Help/Api/POST-api-v1-customer-resetpassword) 

Post Reset Password


| [PUT api/v1/customer/address](/Help/Api/PUT-api-v1-customer-address) 

Update Customer Address


| [GET api/v1/customer/widget/statistics/{EncryptedCustomerId}](/Help/Api/GET-api-v1-customer-widget-statistics-EncryptedCustomerId) 

Get statistics widget


| [GET api/v1/customer/widget/snapshot/{EncryptedCustomerId}](/Help/Api/GET-api-v1-customer-widget-snapshot-EncryptedCustomerId) 

Get snapshot widget


| [POST api/v1/customer/unsubscribe/{email}/{option}](/Help/Api/POST-api-v1-customer-unsubscribe-email-option) 

Unsubscribe Customer



## Lead

Lead

| API Description
| --- ---
| [GET api/v1/lead/{customerid}](/Help/Api/GET-api-v1-lead-customerid) 

Get lead by customer id


| [GET api/v1/lead/{customerid}/detail/{leadid}](/Help/Api/GET-api-v1-lead-customerid-detail-leadid) 

Get detail of lead


| [GET api/v1/lead/status](/Help/Api/GET-api-v1-lead-status) 

Get collection of lead status


| [GET api/v1/lead/source](/Help/Api/GET-api-v1-lead-source) 

Get collection of lead source


| [POST api/v1/lead/add](/Help/Api/POST-api-v1-lead-add) 

Add new lead


| [PUT api/v1/lead/update](/Help/Api/PUT-api-v1-lead-update) 

Update lead


| [DELETE api/v1/lead/delete/{id}](/Help/Api/DELETE-api-v1-lead-delete-id) 

Delete lead


| [POST api/v1/lead/note/add](/Help/Api/POST-api-v1-lead-note-add) 

Add Note


| [PUT api/v1/lead/note/update](/Help/Api/PUT-api-v1-lead-note-update) 

Update note


| [DELETE api/v1/lead/note/delete/{id}](/Help/Api/DELETE-api-v1-lead-note-delete-id) 

Delete note



## Order

Order Controller for manage all order processing operations

| API Description
| --- ---
| [GET api/v1/order/{EncryptedOrderId}](/Help/Api/GET-api-v1-order-EncryptedOrderId) 

Get Order


| [GET api/v1/order/downline/personalorder/{customerId}](/Help/Api/GET-api-v1-order-downline-personalorder-customerId) 

Get Personal Order of downline customer


| [GET api/v1/order/personalorder/{EncryptedCustomerId}](/Help/Api/GET-api-v1-order-personalorder-EncryptedCustomerId) 

Get Personal Order of logged in customer


| [GET api/v1/order/stats/{customerId}](/Help/Api/GET-api-v1-order-stats-customerId) 

Get Order Statistic of customer


| [POST api/v1/order/account/upgrade](/Help/Api/POST-api-v1-order-account-upgrade) 

Post upgrade backoffice account


| [PUT api/v1/order/subscription/{EncryptedSpreedlySubscriberId}](/Help/Api/PUT-api-v1-order-subscription-EncryptedSpreedlySubscriberId) 

Update active subscription, this would affect to RecurringPayment with CustomerRole Product


| [PUT api/v1/order/subscription/{customerId}/cancel](/Help/Api/PUT-api-v1-order-subscription-customerId-cancel) 

Update Subscription Role


| [POST api/v1/order/subscription/{customerId}/renewal](/Help/Api/POST-api-v1-order-subscription-customerId-renewal) 

Renewal Subscription


| [GET api/v1/order/recurring/{EncryptedCustomerId}](/Help/Api/GET-api-v1-order-recurring-EncryptedCustomerId) 

Get Recurring Orders of customer


| [PUT api/v1/order/recurring/{EncryptedCustomerId}/schedule/{RecurringPaymentId}](/Help/Api/PUT-api-v1-order-recurring-EncryptedCustomerId-schedule-RecurringPaymentId) 

Update Schedule of recurring order


| [PUT api/v1/order/recurring/{EncryptedCustomerId}/shipping/{RecurringPaymentId}](/Help/Api/PUT-api-v1-order-recurring-EncryptedCustomerId-shipping-RecurringPaymentId) 

Update Shipping Address of recurring orders


| [PUT api/v1/order/recurring/{EncryptedCustomerId}/paymentmethod/{RecurringPaymentId}/{EncryptedSpreedlyId}](/Help/Api/PUT-api-v1-order-recurring-EncryptedCustomerId-paymentmethod-RecurringPaymentId-EncryptedSpreedlyId) 

Update payment method of selected recurring order


| [PUT api/v1/order/recurring/{EncryptedCustomerId}/products/{RecurringPaymentId}/{storecountryid}](/Help/Api/PUT-api-v1-order-recurring-EncryptedCustomerId-products-RecurringPaymentId-storecountryid) 

Update Recurring order items


| [POST api/v1/order/recurring/{EncryptedCustomerId}/products/{RecurringPaymentId}/{storecountryid}](/Help/Api/POST-api-v1-order-recurring-EncryptedCustomerId-products-RecurringPaymentId-storecountryid) 

Add Recurring order items in recurring orders


| [GET api/v1/order/cart/{customerId}/country/{countryId}](/Help/Api/GET-api-v1-order-cart-customerId-country-countryId) 

Get Collection of shopping cart by customer


| [POST api/v1/order/cart/{customerId}/country/{countryId}](/Help/Api/POST-api-v1-order-cart-customerId-country-countryId) 

Add items to shopping cart


| [PUT api/v1/order/cart/{customerId}/country/{countryId}](/Help/Api/PUT-api-v1-order-cart-customerId-country-countryId) 

Update shopping cart items


| [POST api/v1/order/enrollment/additionalcosts](/Help/Api/POST-api-v1-order-enrollment-additionalcosts) 

Calculate Tax And Shipping for enrollment confirmation step


| [POST api/v1/order/checkout/additionalcosts](/Help/Api/POST-api-v1-order-checkout-additionalcosts) 

Get additional Cost for checkout shopping cart, i.e TotalShipping, TotalDiscount, TotalTax


| [POST api/v1/order/checkout](/Help/Api/POST-api-v1-order-checkout) 

Process a checkout



## Payment

Payment Controller

| API Description
| --- ---
| [GET api/v1/payment/{EncryptedCustomerId}/{countryId}](/Help/Api/GET-api-v1-payment-EncryptedCustomerId-countryId) 

Get payment method collection by customer id


| [GET api/v1/payment/{EncryptedCustomerId}/detail/{EncryptedSpreedlyId}](/Help/Api/GET-api-v1-payment-EncryptedCustomerId-detail-EncryptedSpreedlyId) 

Get payment method detail by customer id


| [POST api/v1/payment/{customerId}](/Help/Api/POST-api-v1-payment-customerId) 

Add new payment method collection by customer id


| [PUT api/v1/payment/{EncryptedCustomerId}/{EncryptedSpreedlyId}](/Help/Api/PUT-api-v1-payment-EncryptedCustomerId-EncryptedSpreedlyId) 

Update payment method collection by customer id


| [GET api/v1/payment/getcardtype/{CountryId}](/Help/Api/GET-api-v1-payment-getcardtype-CountryId) 

Get accepted credit card type


| [GET api/v1/payment/getcardtype](/Help/Api/GET-api-v1-payment-getcardtype) 

No documentation available.


| [GET api/v1/payment/paymentmethodtype/{CountryId}](/Help/Api/GET-api-v1-payment-paymentmethodtype-CountryId) 

Get payment method type


| [GET api/v1/payment/bank/{CountryId}](/Help/Api/GET-api-v1-payment-bank-CountryId) 

Get Bank by country id


| [GET api/v1/payment/kspayrespnosehandler/{clientId}?reCommConId={reCommConId}&reCommType={reCommType}&reHash={reHash}&a1={a1}&rcid={rcid}&rctype={rctype}&rhash={rhash}&authyn={authyn}&trno={trno}&trddt={trddt}&trdtm={trdtm}&amt={amt}&authno={authno}&msg1={msg1}&msg2={msg2}&ordno={ordno}&isscd={isscd}&aqucd={aqucd}&result={result}&halbu={halbu}&cbtrno={cbtrno}&cbauthno={cbauthno}&FromOrder={FromOrder}](/Help/Api/GET-api-v1-payment-kspayrespnosehandler-clientId_reCommConId_reCommType_reHash_a1_rcid_rctype_rhash_authyn_trno_trddt_trdtm_amt_authno_msg1_msg2_ordno_isscd_aqucd_result_halbu_cbtrno_cbauthno_FromOrder) 

KSPAY Handler


| [POST api/v1/payment/kspayrespnosehandler/{clientId}?reCommConId={reCommConId}&reCommType={reCommType}&reHash={reHash}&a1={a1}&rcid={rcid}&rctype={rctype}&rhash={rhash}&authyn={authyn}&trno={trno}&trddt={trddt}&trdtm={trdtm}&amt={amt}&authno={authno}&msg1={msg1}&msg2={msg2}&ordno={ordno}&isscd={isscd}&aqucd={aqucd}&result={result}&halbu={halbu}&cbtrno={cbtrno}&cbauthno={cbauthno}&FromOrder={FromOrder}](/Help/Api/POST-api-v1-payment-kspayrespnosehandler-clientId_reCommConId_reCommType_reHash_a1_rcid_rctype_rhash_authyn_trno_trddt_trdtm_amt_authno_msg1_msg2_ordno_isscd_aqucd_result_halbu_cbtrno_cbauthno_FromOrder) 

KSPAY Handler


| [GET api/v1/payment/austpayrespnosehandler/{clientId}?successcode={successcode}&oid={oid}&austpay_id={austpay_id}&declinedcode={declinedcode}](/Help/Api/GET-api-v1-payment-austpayrespnosehandler-clientId_successcode_oid_austpay_id_declinedcode) 

AUSTPAY Handler


| [POST api/v1/payment/austpayrespnosehandler/{clientId}?successcode={successcode}&oid={oid}&austpay_id={austpay_id}&declinedcode={declinedcode}](/Help/Api/POST-api-v1-payment-austpayrespnosehandler-clientId_successcode_oid_austpay_id_declinedcode) 

AUSTPAY Handler


| [GET api/v1/payment/payoneer/register](/Help/Api/GET-api-v1-payment-payoneer-register) 

Get payoneer registration link


| [POST api/v1/payment/payoneer/register](/Help/Api/POST-api-v1-payment-payoneer-register) 

Get payoneer registration link


| [GET api/v1/payment/payoneer/register/handler/{clientId}/{customerId}/{redirectUrl}](/Help/Api/GET-api-v1-payment-payoneer-register-handler-clientId-customerId-redirectUrl) 

Payoneer register handler


| [POST api/v1/payment/payoneer/register/handler/{clientId}/{customerId}/{redirectUrl}](/Help/Api/POST-api-v1-payment-payoneer-register-handler-clientId-customerId-redirectUrl) 

Payoneer register handler



## Organization

| API Description
| --- ---
| [GET api/v1/organization/{encryptedcustomerid}/personal](/Help/Api/GET-api-v1-organization-encryptedcustomerid-personal) 

Get personal distributor by customer id


| [GET api/v1/organization/{encryptedcustomerid}/unilevel](/Help/Api/GET-api-v1-organization-encryptedcustomerid-unilevel) 

Get unilevel distributor by customer id


| [GET api/v1/organization/{encryptedcustomerid}/unileveltree/{maxlevel}](/Help/Api/GET-api-v1-organization-encryptedcustomerid-unileveltree-maxlevel) 

Get unilevel distributor by customer id for Unilevel Tree


| [POST api/v1/organization/{customerid}/binary](/Help/Api/POST-api-v1-organization-customerid-binary) 

Get binary distributor by customer id


| [GET api/v1/organization/{encryptedcustomerid}/customer](/Help/Api/GET-api-v1-organization-encryptedcustomerid-customer) 

Get personal customer by customer id


| [GET api/v1/organization/ranks/{CustomerId}](/Help/Api/GET-api-v1-organization-ranks-CustomerId) 

Get all of ranks with description


| [GET api/v1/organization/binary/{CustomerId}/{DownlineCustomerId}](/Help/Api/GET-api-v1-organization-binary-CustomerId-DownlineCustomerId) 

Get Graphical Genealogy of Customer ID


| [GET api/v1/organization/binary/{CustomerId}/all](/Help/Api/GET-api-v1-organization-binary-CustomerId-all) 

No documentation available.


| [GET api/v1/organization/unilevel/{CustomerId}/{DownlineCustomerId}](/Help/Api/GET-api-v1-organization-unilevel-CustomerId-DownlineCustomerId)
| [GET api/v1/organization/binarypositon/{customerId}/{positionId}](/Help/Api/GET-api-v1-organization-binarypositon-customerId-positionId) 

Get bottom binary postition id based on customer id and position


| [GET api/v1/order/statistic/geoanalytics/{EncryptedCustomerId}](/Help/Api/GET-api-v1-order-statistic-geoanalytics-EncryptedCustomerId) 

Get customer count by geographic area


| [GET api/v1/organization/chart/unilevel](/Help/Api/GET-api-v1-organization-chart-unilevel) 

Get Organization Chart


| [GET api/v1/organization/scoreboard/{CustomerId}/rank/{GenealogyTypeId}](/Help/Api/GET-api-v1-organization-scoreboard-CustomerId-rank-GenealogyTypeId) 

Get list of scoreboard, Grouped by GenealogyTypeId


| [GET api/v1/other/scoreboard/{CustomerId}/rank/{GenealogyTypeId}](/Help/Api/GET-api-v1-other-scoreboard-CustomerId-rank-GenealogyTypeId) 

Get list of scoreboard, Grouped by GenealogyTypeId


| [GET api/v1/organization/rankadvancement/{EncryptedCustomerId}](/Help/Api/GET-api-v1-organization-rankadvancement-EncryptedCustomerId) 

Get rank advancement


| [GET api/v1/other/rankadvancement/{EncryptedCustomerId}](/Help/Api/GET-api-v1-other-rankadvancement-EncryptedCustomerId) 

Get rank advancement


| [GET api/v1/organization/personal/sponsorupdate](/Help/Api/GET-api-v1-organization-personal-sponsorupdate) 

Get collection of eligble customer id to change their sponsor


| [PUT api/v1/organization/personal/sponsorupdate](/Help/Api/PUT-api-v1-organization-personal-sponsorupdate) 

Submit Sponsorship Update


| [GET api/v1/organization/top10/leadershipactivity](/Help/Api/GET-api-v1-organization-top10-leadershipactivity) 

Display top 10 customers from organization


| [GET api/v1/organization/faststart](/Help/Api/GET-api-v1-organization-faststart) 

A widget for Fast start information



## Product

| API Description
| --- ---
| [GET api/v1/product/{productid}/{customerid}/{storecountryid}](/Help/Api/GET-api-v1-product-productid-customerid-storecountryid) 

Get product detail by Id


| [GET api/v1/product/{customerId}/category/{categoryId}/country/{countryId}](/Help/Api/GET-api-v1-product-customerId-category-categoryId-country-countryId) 

Get list of products by category id


| [GET api/v1/product/{customerId}/category/{categoryId}/country/{countryId}/recurring](/Help/Api/GET-api-v1-product-customerId-category-categoryId-country-countryId-recurring) 

Get list of products by category id for recurring order


| [GET api/v1/product/GetFinalPrice/{productid}/{customerid}/{storecountryid}](/Help/Api/GET-api-v1-product-GetFinalPrice-productid-customerid-storecountryid) 

Get final price of product


| [GET api/v1/product/account/upgrade](/Help/Api/GET-api-v1-product-account-upgrade) 

Get Product Account Upgrade by Customer Id


| [GET api/v1/product/subscription/renewal](/Help/Api/GET-api-v1-product-subscription-renewal) 

Renewal Subscription


| [GET api/v1/product/enrollment/{countryid}](/Help/Api/GET-api-v1-product-enrollment-countryid) 

Get Enrollment Product list for Rep's enrollment by country


| [GET api/v1/product/enrollment/{countryid}/customer](/Help/Api/GET-api-v1-product-enrollment-countryid-customer) 

Get Enrollment Product list for Customer's enrollment by country


| [GET api/v1/product/enrollment/{countryid}/autoship](/Help/Api/GET-api-v1-product-enrollment-countryid-autoship) 

Get Enrollment Product Autoship list for Rep's enrollment by country


| [GET api/v1/product/enrollment/{countryid}/autoship/customer](/Help/Api/GET-api-v1-product-enrollment-countryid-autoship-customer) 

Get Enrollment Product Autoship list for Rep's enrollment by country


| [GET api/v1/product/{customerid}/category](/Help/Api/GET-api-v1-product-customerid-category) 

Get list of Category by customerid



## Image

Get Image from backend

| API Description
| --- ---
| [POST api/v1/image/{PictureId}](/Help/Api/POST-api-v1-image-PictureId) 

Get picture by picture id


| [POST api/v1/image?PictureIds={PictureIds}](/Help/Api/POST-api-v1-image_PictureIds) 

Get list of pictures by collection of pictureid. Caution, many requests id will give a long time response. Recommended to use get by id instead


| [GET api/v1/image/{image}/{height}/{width}](/Help/Api/GET-api-v1-image-image-height-width) 

Resize the profile image. Set 0 for height or width parameter to make good proportions. ex api/v1/image/cloudinary/100/0, api/v1/image/cloudinary/100/50, api/v1/image/cloudinary/0/50


| [POST api/v1/image/remove?EncryptedCustomerId={EncryptedCustomerId}](/Help/Api/POST-api-v1-image-remove_EncryptedCustomerId) 

Remove Profile Image


| [POST api/v1/image/upload/{EncryptedCustomerId}](/Help/Api/POST-api-v1-image-upload-EncryptedCustomerId) 

Update Profile Image, Jquery Function http://jsfiddle.net/vantian58/hkLsx9my/


| [POST api/v1/image/upload/profile?EncryptedCustomerId={EncryptedCustomerId}](/Help/Api/POST-api-v1-image-upload-profile_EncryptedCustomerId) 

Update Profile Image

