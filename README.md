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

## Hypothesis

Access to data is critical to the success of any business. Easily accessible data enables
companies to move quickly, focus on their product and build a data-informed culture
where access leads to better strategies and decisions. 

## Solution

Combining my previous experience in database administration with my iOS Software
Engineering skills I have create `Pro Mujer prototype app`, which will give Pro Mujer client
advisors remote, user-friendly access to client data.
To develop this prototype, I created a simulated version of Pro Mujer’s technical
infrastructure by building the following pieces:
<details>
<summary>Database Server</summary>
  Configuration of a virtual server that simulates Pro Mujer’s production
database.
</details>
<details>
<summary>Web Server</summary>
  Configuration of a virtual serve that receives data requests, connects to
the database, and responds to data requests by sending a json file
</details>
<details>
<summary>Router Configuration</summary>
  Receives internet data requests and forwards to the web server
</details>
<details>
  <summary>App Development for iPads and iPhones</summary>
  Makes data requests via an IP public address to obtain json file converting
information to a user-friendly interface
  </details>

## Demo App
| Log In | Show offices |
|:-------------:|:------------:|
|  <img src="https://github.com/mrugama/ProWomen/blob/master/PMLogIn.gif" width="358" height="626"> | <img src="https://github.com/mrugama/ProWomen/blob/master/PMNOficinas.gif" width="358" height="626"> |
