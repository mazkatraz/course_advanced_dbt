# Bingeflix Docs
{% docs bingeflix_docs %}
This file contains docs blocks for Bingeflix sources
{% enddocs %}

## Common Fields

{% docs bingeflix_event_id %}
The unique identifier of the event.
{% enddocs %}

{% docs bingeflix_subscriptions_plan_id %}
The unique identifier of the subscription plan.
{% enddocs %}

{% docs bingeflix_user_id %}
The unique identifier of the Bingeflix user.
{% enddocs %}

## Ads Table
{% docs table_ads %}
This table contains information about Bingeflix's marketing ads.
{% enddocs %}

{% docs ads_campaign_id %}
The unique identifier of the ad campaign.
{% enddocs %}

{% docs ads_cpm %}
The average cost per 1,000 impressions.
{% enddocs %}

{% docs ads_ctr %}
The average click-through rate on ads served.
{% enddocs %}

{% docs ads_date %}
When the ad campaign was served.
{% enddocs %}

{% docs ads_spend %}
The amount spent on the ad campaign.
{% enddocs %}

## Events Table
{% docs table_events %}
This table contains information about the behavioral events of users while they interact with the Bingeflix platform. It includes events such as logins, logouts, videos watched, and CTA/button clicks.
{% enddocs %}

{% docs event_created_at %}
When the event was logged.
{% enddocs %}

{% docs event_name %}
The name of the event.
{% enddocs %}

{% docs event_session_id %}
The unique identifier of the session in the Bingeflix application.
{% enddocs %}

## Subscriptions
{% docs table_subscription %}
This table contains subscription-related information, such as subscription plan IDs, subscription start dates, renewal dates, billing information, and any other relevant subscription details.
{% enddocs %}

{% docs subscription_id %}
The unique identifier of the subscription.
{% enddocs %}

{% docs subscription_ends_at %}
When the subscription plan ends (The value is NULL if the subscription plan has auto-renew turned on/does not have a defined end date.)
{% enddocs %}

{% docs subscription_starts_at %}
When the subscription plan starts.
{% enddocs %}

## Subscription Plans
{% docs table_subscription_plans %}
This table contains information about the subscription plans available at Bingeflix.
{% enddocs %}

{% docs subscription_plan_name %}
he name of the subscription plan.
{% enddocs %}

{% docs subscription_plan_payment_period %}
The cadence of the payment period for the subscription plan (e.g., monthly, annually).
{% enddocs %}

{% docs subscription_plan_pricing %}
The price of the subscription plan per payment period.
{% enddocs %}

## Users
{% docs table_users %}
This table stores information about Bingeflix users, including user IDs, usernames, email addresses, subscription start dates, and other relevant user details.
{% enddocs %}

{% docs user_birthdate %}
The user's birthdate.
{% enddocs %}

{% docs user_created_at %}
When the user's account was created.
{% enddocs %}

{% docs user_country %}
The country the user resides in.
{% enddocs %}

{% docs user_deleted_at %}
When the user's account was deleted (This is NULL if the account is not deleted.).
{% enddocs %}

{% docs user_email %}
The user's email.
{% enddocs %}

{% docs user_name %}
The user's full name.
{% enddocs %}

{% docs user_phone_number %}
The user's phone number.
{% enddocs %}

{% docs user_region %}
The state or region the user resides in.
{% enddocs %}

{% docs user_sex %}
The user's sex at birth.
{% enddocs %}

{% docs user_username %}
The username used for login.
{% enddocs %}