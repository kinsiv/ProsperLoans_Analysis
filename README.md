# Risk Assessment & Forecast of Loan Defaults, Data Wrangled from Prosper
Loan approval strategy success is awarded based on foresight and caution. These are only accomplished when an examination of both the customer and previous outcomes of customers with similar demographics is conducted. Any financial organization or bank understands that loans can be a complete miss. Situations happen where the loan is defaulted on, which can result in a total loss for the bank. Quantifying the measurements of instances like these, also of successful instances where the loan is paid in full, can create a model to predict the outcome. When this approach is taken, unrealized profit can be obtained while risk is mitigated. Industries around the globe classify customers in this manner. Prosper should have a similar process given its eligibility to do so. This project evaluates Prosper’s current model and provides a model that predicts if a customer’s loan will be a success or failure.

## Research Quesitons:
1. Are classifications or measurements evaluated by Prosper regarding loan applicants utilized in alotting them conditions?
2. Can loan outcomes be predicted for new customers who apply and subsequently forecast a profit margin?
3. Is there an underlying theme among customers that default? Do relationships exist between variables that can measure this phenomenon?

## Actionable & Business Insights:
*Financial evaluations are calculated on profit average ($6,783.58) and derived from compound interest equation (yearly compound) with population averages entered. APR = 22%, length = 36 months, loan principal amount = $8314.76.*
1. Integrate 99.4% accuracy forecast model into the approval process to realize profit of $226,208,838 for a 258% gain over the next 55,071 loans.

![image](https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/b2a2f892-19c6-4921-a25e-764a24a4d884)


<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

2. ROI loss due to unpaid principle amounts at $2,789,880 from $141,434,067 from K-Nearest Neighbor machine learning algorithm.

![image](https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/8b3b5c01-80d9-4fa2-b9d2-d43b508ebefe)


<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

### Proposed Red Flag System
*Prosper Rating is a numeric scale which summarizes financial aspects of a customer, from their loan request. Lower scores have more cash associated with the loan.*

3. Credit scores are heavily weighed against a person's bankcard utilization, as higher ratios are found sooner to default on loans. The chart shows how Poor & Fair utilize credit exceedingly more than counterparts. These customers should have restricted loan amounts.
* Average (%) Estimated: .657, Confidence Interval: [.665, .649], CL: 97.5%

![image](https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/93ca6d23-dfe8-4082-aa95-f03b62ae6db9)


<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

4. Prosper Ratings of 1 & 2 show potential Estimated Loss potential that can be troublesome for that account's revenue. This can be mitigated with APR and additional fees.
* Average (%) Estimated Loss: .155, Confidence Interval: [.152, .157], CL: 97.5%

![image](https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/fcf5fd69-db60-4152-820b-f1c3b1e480cd)

<div align="center">
    <img src="https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/2ae8ad63-a12e-40d9-9d18-b593d13c7f01" alt="Your Image"/>
</div>

5. Preferred DTR ratio is <=.36, which a new user is 85.08% likely to ascertain. There's risky approvals handed out to unsatisfactory DTRs of >=.43, which a new user is 4.95% likely to ascertain. Denial of these applications can lead to fewer defaults, as is industry standard.
* Estimate: .36, Confident Interval: [.359, .36], CL: 97.5%
* Estimate: .43, Confidence Interval: [.428, .432], CL: 97.5%

![image](https://github.com/kinsiv/ProsperLoans_Analysis/assets/89998643/25717cd7-57d2-4fa6-ae54-f449070c8de6)

