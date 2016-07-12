INFLATION
Inflation is a sustained increase in the general level of prices for goods and services. As inflation rises, every unit of currency buys a smaller quantity of goods and services.
The factors that influence inflation most are the interest rates, supply and prices.
The factors that contribute to a change in the level of inflation:

->Interest rate: When there is a decrease in the interest rate, more number of industries and individuals borrow money leading to an increase in money supply, public savings and consumer spending. These in turn result in a rise in employment and aggregate demand. Monetarists believe that an increase in demand leads to higher levels of inflation.

->Money supply: Inflation is caused by an increase in money supply which leads to an increase in aggregate demand. The higher the money supply, the higher is the rate of inflation. Money supply may increase with the expansion of private sector or the repayment of public debt by the government.

->Disposable income: An increase in disposable income results from an increase in national income or employment. When the disposable income of the people increases, it raises their demand for goods and services. Reduction of tax rate also results in a higher disposable income.

->Government expenditure: Government expenditure increases with the expansion of government activities, which result in a rise of demand for goods and services.

->Black money: Tax evasion and corruption promote an increase in black money, which in turn leads to an increased demand. People spend such easy money extravagantly, thereby creating unnecessary demand for goods and services.

->Deficit financing: In order to compensate its increasing expenses, the government adopts deficit financing by borrowing from the public and even by printing more notes. This raises the aggregate demand in relation to the aggregate supply, there by leading to inflationary rise in prices. This is also known as deficit-induced inflation.

->Oil prices: Oil prices and inflation are often seen as being connected in a cause and effect relationship. As oil prices move up or down, inflation follows in the same direction.

->Resources: Shortage of resources such as manpower, raw materials, capital etc. lead to reduction in the supply of goods and services which in turn results in inflationary rise of prices. Industrial disputes decrease the productivity of manpower; natural calamities adversely affect the supply of food products and raw materials; artificial scarcities are created by speculators and hoarders who indulge in black marketing – these three factors lead to a drastic decrease in the availability of resources.

->Exports: When the country produces more goods for exports that for domestic use, it leads to an increase in aggregate demand in relation to the aggregate supply, there by contributing to inflation.

Effect of decision and utility nodes:

In the previous version of the project, the temporality is modeled for the inflation node using a self loop – this approach gives a lot of insight into how the future states of inflation are affected depending on the previous states. However, this approach fails to consider the real time decision making that is to be done in the case of inflation in a country’s economy.

In every country, the chairperson of Federal Reserve Bank will meet with the President, Senate and the financial advisors to take a decision regarding interest rates – either to raise, lower or maintain the same interest rates. This process is explained below:

->Decrease in inflation: In this case, the interest rates need to be lowered so that it leads to increased money flow which in turn leads to employment and an increase in inflation.

->Increase in inflation: In this case, the interest rates need to be raised to result in a tight monetary policy which in turn leads to a decrease in inflation.

->Decision node: The node ‘Interest Rate’ is made into a decision node which accounts for the decision that is made – it tells us how the future decisions are dependent on the past decision nodes.

->Utility node: The utility node ‘Benefit’ represents the acquired gain due to the decision that is made. That means it gives a quantified value of the advantage of making a decisioin.

Example: If the inflation increases, we need to raise the interest rates to lower the inflation. When this decision is made, the value corresponding to raise in interest rates shows the benefit of making that decision.

Instructions:
1. Go to Network>Expand Time. Enter Amount of time:2 and Burn in time :2

2. Compile the Net
Sample Test Cases:
1. If inflation [0] is present, interest rates [0] need to be raised. (Result: The benefit of raise in interest rates is higher - 113)

2. If inflation [0] is absent, interest rates [0] need to be lowered. (Result: The benefit of lowering the interest rates is higher - 112)

3. If inflation [0] is present, interest rates [0] need to be raised. (Result: The benefit of raise in interest rates is higher - 113). Now an optimal decision is to be taken, that is raise the interest rates [0] – this leads to an increase in benefit of raise in interest rates [1] (value: 113), now again if an optimal decision is made to increase the interest rates [1], then this results in lowering the presence of inflation in future cases i.e, inflation [1] (value: 41.3%).

4. If inflation [0] is absent, interest rates [0] need to be lowered. (Result: The benefit of lowering the interest rates is higher - 112). Now an optimal decision is to be taken, that is lowering the interest rates [0] – this leads to an increase in benefit of raising the interest rates [1] (value: 112), now again if an optimal decision is made to increase the interest rates [1], then this results in lowering the presence of inflation in future cases, i.e, inflation [1] (value: 40.6%)
Note: Ultimate aim is to make optimal decisions and decrease the presence of inflation.
