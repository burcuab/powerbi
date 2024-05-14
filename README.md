# How to use Whatif parameters in Power BI 

In this Power BI sample report; I get input from users as change percentage in Sessions, Conversion Rate and AOV. Accordingly, Revenue and Transactions metrics whatif values are being calculated and visualized dynamically.

![image](https://github.com/burcuab/powerbi/assets/125803633/1a602ae2-ec9f-48ec-afe4-bb26706930c4)

How to create WhatIf parameters; 

Go to Modeling > New parameter
It can be Numeric range or fields. I wanted to use decimal range between -1 and 1 and it increments by 0.01 in slider. So I used it as change percentage in whatif metric calculations.

I used 3 parameters for Sessions, Conversion Rate and AOV. Each parameter and parameter value is defined as below.

![image](https://github.com/burcuab/powerbi/assets/125803633/60a21529-3ff2-405b-9594-e4385ac1c2f8)

![image](https://github.com/burcuab/powerbi/assets/125803633/1a283ba9-d8f1-40ef-9e2a-577065c71a44)

I used it in Whatif metric calculations. Here is the Revenue Whatif metric calculation;

![image](https://github.com/burcuab/powerbi/assets/125803633/8778ccf1-3097-48d5-b942-364ec0eddcda)

[See here for power bi desktop file of this example].()
