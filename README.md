# A/B Testing - Optimizing Loan Repayment Campaigns

# Logo

# PAYZEN
PayZen is a digital financial platform empowering individuals across Africa to take control of their finances with ease. From managing repayments and accessing instant loans to making smart investments, PayZen simplifies financial decisions with transparency, flexibility, and innovative technology, wuth a mission to create financial freedom and inclusion for everyone, whether in city centers or rural communities

## Problem Statement

Digital loan recovery campaigns at PayZen rely heavily on automated SMS and WhatsApp reminders. However, repayment rates in early-stage delinquency remain inconsistent, and it is unclear which message framing most effectively motivates customers to take action. Current campaigns use generic reminder language, which may not resonate equally across customer segments or behavioral contexts. This results in the following baseline KPI standings:

🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴 - Check these - didnt use Avg time to repay
 - Repayment Rate: 48%
 - Repayment Mix: 65% Partial | 35% Full
 - Response Rate: 15%
 - Avg Time to Repayment: 10 days

## Campaign Objective

To increase loan repayment rates in early-stage delinquency (1–7 days past due) by optimizing the messaging used in automated recovery campaigns, while maintaining a positive customer experience.

## Hypothesis

#### Primary Hypothesis

Customers who receive empathetic, supportive repayment messages will have a higher repayment rate than customers who receive standard, transactional repayment reminders.

#### Null Hypothesis

There is no significant difference in repayment rates between customers who receive empathetic messages and those who receive standard repayment reminders.

#### Expected Impact Direction

 - Positive uplift in repayment rate for the empathetic message variant

- Secondary expected effects:
  - Higher response rate
  - Faster time to repayment
  - Improved customer sentiment (qualitative)


## Test Scope & Assumptions

 - Campaign Type:
    - Automated digital recovery campaign
 - Channels:
    - Whatsapp
 - Customer Stage:
    - Early-stage delinquency (1–7 Days Past Due)
 - Geographic Scope:
    - Single market
 - Test Duration:
    - Fixed campaign window (e.g., 14 days)

## Variants Definition
#### Control Group (Variant A – Standard Reminder)
  - Message Type: Transactional / neutral reminder
  - Purpose: Represents the current baseline messaging used in recovery campaigns

  - Message:
     - “Your loan repayment is overdue. Please make payment immediately to avoid additional charges.”

#### Test Group (Variant B – Empathetic Framing)
  - Message Type: Supportive / empathetic reminder
  - Purpose: Tests whether emotional and supportive language improves repayment behavior

  - Message:
     - “We understand that unexpected challenges can arise. Making your repayment today helps you stay in good standing and continue accessing our services.”

#### Variable Being Tested
  - Single Variable: Message framing (tone and wording)
  - All other factors remain constant:
     - Channel
     - Timing
     - Frequency
     - Customer eligibility





## Target Population

🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴 - Ensure below are in end data
Customers who meet all of the following criteria:
 - Active loan customers
 - 1–7 days past due (DPD)
 - Loan size (small vs medium)
 - No active dispute or repayment plan
 - Eligible for automated digital recovery outreach

## Metrics & Success Criteria
#### Primary Metric

 - Repayment Rate (%)
      - Percentage of customers in each variant who successfully repay their loan within the test window.

 - Secondary Metrics

      - Response Rate (%) – Percentage of customers who reply or engage with the message
      - Time to Repayment – Average time (in days) from message sent to repayment
      - Partial vs Full Repayment – Distribution of repayment completeness

🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴 - check if gonna use
Success Criteria
Statistical Significance: p-value < 0.05 between variants
Business Significance: Minimum +5% uplift in repayment rate to justify scaling
Positive trends in secondary metrics considered supportive evidence


## Data Set
