![PROMUJERico](https://promujer.org/content/themes/storyware/resources/assets/build/svg/logo.svg)

## Who we are

Pro Mujer was founded in 1990 in El Alto, Bolivia, by two visionary leaders, Lynne Patterson and Carmen Velasco, who believed that given the right opportunities, women can become powerful agents of change.

From a pioneering experiment in micro-lending, Pro Mujer has become one of Latin America’s leading women’s development organizations. Our integrated approach offers access to finance, health and educational services. These are delivered in supportive social spaces that foster community building and equip them with education and tools to take on the challenges they face daily.

<details>
<summary>Who we serve</summary>

### Every woman has a unique story and background
Going beyond small loans, we support our entrepreneurial clients on their own transformative journey by creating opportunities, providing education, training and leadership skills to help them grow their businesses.
</details>

## Problem

According to Amplitude, “74% of businesses say that they want to be data-driven, but
only 29% say they are good at connecting analytics to action. If you can’t quickly and
easily get actionable insights from your data, unite your company around that insight,
and make product or business decisions from it, then you aren’t data-driven.”
As a former database administrator for Pro Mujer Nicaragua, I witnessed first-hand the
importance of making data-driven decisions to meet client needs. Without timely access
to data, Pro Mujer asesores (client advisors) experience limitations to providing financial
information and products to clients.

## The Hypothesis

Access to data is critical to the success of any business. Easily accessible data enables
companies to move quickly, focus on their product and build a data-informed culture
where access leads to better strategies and decisions. 

## Solution

`Pro mujer` app is going to solve the accessibility of the information and this is going to help manager to make decision from their own data. In order to reach this target we need the next steps:
<details>
<summary>ETL Process</summary>
  Production database (Extract data):
  Extract an exact copy of the database, with the aim of not overstressing the production server this extraction should be in non-working hours.
  
  Staying database (Transform data)
  From the exact copy we proceed to transformation and validation.
  
  Data warehousing (Load data)
  The loading of the data once processed will be stored in a data warehousing that we will use for future queries.
</details>
<details>
<summary>Web service</summary>
  Configure IIS:
  Implement Web API (CSharp).
</details>
<details>
<summary>Network</summary>
  Configure router (Port forwarding).
</details>
<details>
  <summary>App for iPads or iPhones (to display info)</summary>
  </details>

## Demo App
| Log In | Show offices |
|:-------------:|:------------:|
|  <img src="https://github.com/mrugama/ProWomen/blob/master/PMLogIn.gif" width="358" height="626"> | <img src="https://github.com/mrugama/ProWomen/blob/master/PMNOficinas.gif" width="358" height="626"> |
