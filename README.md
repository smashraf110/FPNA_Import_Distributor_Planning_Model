# FPNA_Import_Distributor_Planning_Model

# Overview
Built an integrated FP&amp;A planning model simulating a European import distributor. The model includes revenue drivers, FX sensitivity, working capital roll-forward, EBITDA-to-cash bridge, and revolving credit facility logic to evaluate growth sustainability and funding risk under multiple scenarios.

The objective of this model is not to create a static budget template. Instead, it was designed to manage advanced FP&A responsibilities, including:

 ⇒ Evaluating whether growth is self-funded
 
 ⇒ Understanding how working capital affects liquidity
 
 ⇒ Stress-testing profitability under FX volatility
 
 ⇒ Assessing the need for external financing
 
 ⇒ Identifying liquidity risk under receivable deterioration
 

The model integrates the income statement, working capital dynamics, and financing structure into a unified planning framework.

It is structured to support management decision-making under both base-case and stress scenarios.

# Model Structure
The model is organized into interconnected layers to reflect how financial performance flows through operations, working capital, and liquidity.

# Revenue Engine
The revenue engine is fully driver-based and includes:

 ⇒ Active contract customers
 
 ⇒ New customer acquisition per quarter
 
 ⇒ Orders per customer per month
 
 ⇒ Average order value
 
 ⇒ Spot sales as a percentage of revenue
 
 ⇒ Annual price adjustment
 
This structure allows revenue to be flexibly adjusted under growth or pricing scenarios.

# Operating Model
The operating model integrates:

 ⇒ Supplier cost as a percentage of revenue
 
 ⇒ FX sensitivity applied to supplier cost
 
 ⇒ Freight and logistics variable costs
 
 ⇒ Commercial, warehouse, and administrative payroll drivers
 
 ⇒ Marketing as a percentage of revenue
 
The output is monthly and annual EBITDA with margin analysis.

This ensures profitability is dynamically linked to operational drivers rather than hardcoded assumptions.

# Working Capital Layer
The working capital module includes:

 ⇒ Accounts receivable (DSO-driven)
 
 ⇒ Inventory coverage (months-based logic
 
 ⇒ Accounts payable (DPO-driven)
 
 ⇒ Net Working Capital (NWC) calculation
 
 ⇒ Monthly change in NWC
 
 ⇒ Operating cash flow calculation
 
An annual "EBITDA-to-Operating Cash Flow bridge" reconciles profitability to cash generation.

This section highlights capital intensity and liquidity sensitivity.

# Financing Layer
The financing structure includes

 ⇒ Revolving Credit Facility (RCF) logic
 
 ⇒ Credit limit control
 
 ⇒ Over-limit breach detection
 
 ⇒ Monthly RCF utilization
 
 ⇒ Interest cost calculation

 This allows the model to simulate whether growth can be funded internally or requires external financing.
 
Liquidity risk becomes visible when operating cash flow is insufficient to cover working capital expansion.

# Scenario Controls
The model allows controlled stress testing through adjustable inputs:

 ⇒ Volume growth adjustments
 
 ⇒ AR days override
 
 ⇒ FX rate shock
 
 ⇒ OPEX adjustment
 
 ⇒ Supplier payment terms
 
These scenario toggles make the model suitable for strategic planning discussions rather than static forecasting.

# Executive Dashboard
Two dashboards were developed:

  # Cash & Growth Control Dashboard:
  
   ⇒ Revenue and EBITDA trends
   
   ⇒ Cash position tracking
   
   ⇒ RCF utilization
   
   ⇒ Key performance indicators

  # Operating & Liquidity Performance Dashboard
  
   ⇒ EBITDA-to-Cash bridge
   
   ⇒ Working capital impact analysis
   
   ⇒ Liquidity risk metrics
   
   ⇒ Financing exposure overview
   
The dashboards translate financial mechanics into decision-support visuals.

# Key Insights
The most important insight from this model is the gap between EBITDA and cash generation.

In the base scenario:

 ⇒ EBITDA (Year): €476k
 
 ⇒ Operating Cash Flow (Year): €330k
 
Approximately €146k of EBITDA was absorbed by working capital expansion (AR and Inventory growth partially offset by AP).

This demonstrates a fundamental finance principle:

Profitability does not guarantee liquidity.

Even with positive EBITDA, aggressive growth combined with long receivable cycles can create funding pressure.

  The model highlights how:

 ⇒ AR deterioration significantly impacts liquidity
 
 ⇒ Inventory intensity drives capital requirements
 
 ⇒ Supplier terms can partially offset working capital pressure
 
 ⇒ Growth sustainability depends on cash conversion efficiency

This reinforces the importance of working capital discipline in distribution businesses.

# Scenario Testing Example – AR Shock
One stress scenario tested the impact of extending receivable days from 45 to 60.

  Results:
  
  ⇒ Significant increase in AR balance
  
  ⇒ Reduction in operating cash flow
  
  ⇒ Increased reliance on revolving credit facility
  
  ⇒ Higher funding exposure under growth conditions

Despite maintaining positive EBITDA, liquidity deteriorated rapidly.

  This illustrates that:
  
  ⇒ Receivable management is a primary liquidity lever.
  
  ⇒ Under growth and FX pressure, AR discipline becomes critical to avoid breaching financing limits.

# Conclusion
This project demonstrates an integrated FP&A planning approach combining:

 ⇒ Driver-based revenue forecasting
 
 ⇒ Working capital management
 
 ⇒ Liquidity stress testing
 
 ⇒ Financing structure analysis

The model is structured to replicate real-world FP&A and Finance Business Partner responsibilities focused on capital allocation, cash visibility, and risk management.

