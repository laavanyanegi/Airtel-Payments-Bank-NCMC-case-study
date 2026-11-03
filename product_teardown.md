<h1>Airtel Thanks App - RuPay NCMC Recharge</h1>
<h2>Product Teardown</h2>
<p>By <strong>Laavanya Negi</strong></p>
<h2>About&nbsp;</h2>
<p>The &lsquo;Airtel Thanks&rsquo; app allows customers to recharge their Airtel Payments Bank Rupay NCMC cards on the go. With over 500 million downloads on android and &ndash; on app store, the app provides online recharge services of SIM and WiFi, as well as online banking via Airtel Payments Bank.&nbsp;</p>
<p>Airtel Payments Bank caters to three distinct segments - Urban Digital, Underbanked, and Industries &amp; Institutions- offering comprehensive end-to-end digital banking solutions alongside a bouquet of digital financial services including insurance, lending, and investment solutions.&nbsp;</p>
<p>The bank offers the NCMC (National Common Mobility Card) service, allowing millions of users to shop and commute hasslefree from a one-stop solution. The postpaid card had a tied-up with the Delhi Metro Rail Corporation (DMRC) in May 2026 to launch co-branded RuPay &lsquo;On-The-Go&rsquo; Cards, enabled with NCMC, allowing daily commuters to pay for metro travel across multiple cities and transit systems using a single open-loop card. As per the blog published on April 7, 2025, <a href="https://www.airtelpayments.bank.in/social/news/airtel-payments-bank-launches-one-card-for-everything">the Bank has issued over 2.5 million cards to date</a>.</p>
<p><strong><a href="https://x.com/OfficialDMRC/status/2053369695861125434" target="_blank">Airtel - DMRC Announcement Post</a>&nbsp;</strong></p>
<h2>Value Proposition</h2>
<p>As mentioned on the official website, &ldquo;The Airtel Payments Bank RuPay On-The-Go Card provides users a seamless and secure way to make daily digital payments.&rdquo; The card aims to eliminate the need for multiple payment methods, offering a unified solution for seamless and safe payments across various platforms. Stating it is &ldquo;<a href="https://www.airtelpayments.bank.in/social/blogs/how-rupay-ncmc-makes-your-transit-journey-simpler-and-faster">designed to make your daily commute faster, smarter, and more convenient</a>.&rdquo; Equipped with Near-Field Communication (NFC) features, it encourages customers to enjoy the convenience, speed, and security of a single card for all their daily digital payment needs&mdash;from travel and shopping to online transactions.&nbsp;</p>
<h2>User Segmentation</h2>
<p>To segment the users of the Airtel Thanks app exclusively for the Airtel Payments Bank feature, we can divide them into the following categories:&nbsp;</p>
<table>
<tbody>
<tr>
<td>
<p>Segments&nbsp;</p>
</td>
<td>
<p>Description&nbsp;</p>
</td>
<td>
<p>Use Cases&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Frequent Commuters</p>
</td>
<td>
<p>Daily commuters use the card on a regular basis for the metro as well as other monetary transactions.</p>
</td>
<td>
<p>Scenario 1: Daily office commuters recharging the NCMC card on-the-go</p>
<p>Scenario 2: College students travelling in fixed budgets in metro daily to attend classes&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Occasional Commuters</p>
</td>
<td>
<p>Users whose primary transportation medium is not the Delhi metro, who own the card but travel less frequently.</p>
</td>
<td>
<p>Scenario 1: Old people travelling across city to visit their especially doctor or relatives once or twice a month&nbsp;</p>
<p>Scenario 2: vehicle-owners taking the metro on congested days/ protest days/ rainy or thunderstorm days to avoid jammed traffic&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Onboarded First-time Users</p>
</td>
<td>
<p>New users introduced to the Airtel payments bank RuPay NCMC service, freshly onboarded to the app.&nbsp;</p>
</td>
<td>
<p>Scenario 1: School student who recently got a metro card for school and further college commute</p>
<p>Scenario 2: Tourist wandering the city and wants to take the card back home as souvenir&nbsp;</p>
</td>
</tr>
</tbody>
</table>
<h2>User Persona &amp; Journey Mapping</h2>
<p>Persona 1: Rohan, The College Day Scholar (18-24 yrs)</p>
<p>Persona 2: Anitha, A Working Single Mother (40-55 yrs)</p>
<p>Persona 3: Ramesh, Senior Citizen on Foot (60-70 yrs)</p>
<p><strong><a href="https://miro.com/app/board/uXjVH3Fcnpw=/">Airtel Thanks App - Miro board</a></strong></p>
<h3><strong>User Persona Prioritization&nbsp;</strong></h3>
<p>With too many screens for a simple recharge process being the common denominator for all three personas, for this project, we will explicitly prioritise <strong>Rohan</strong>, the student who covers all the areas of development.&nbsp;</p>
<h3><strong>Pain Points Prioritization</strong></h3>
<p>An on-the-go student who needs minimum yet frequent recharges usually while climbing the metro stairs or near the turnstile, friction was observed where the minimum cost for recharge is suggested to be ₹100, which is not helpful for a one-way travel top-up. He also struggled with finding the NFC top-up button immediately after a successful transaction.&nbsp;</p>
<p>This allowed for opportunities where quick select suggestions of smaller amounts like ₹50 could help his overall interaction with the app. Another opportunity opens up with the live payment status bar clearly mentioning the steps remaining for the recharge to appear on top. Lastly, once the transaction is completed, an instant NFC-sync prompt/pop-up can be triggered to ensure a complete experience.</p>
<h2>Problem Statement&nbsp;</h2>
<p>Reviews across platforms observed that frequent commuters, who are usually on the time crunch, struggle to quickly identify the recharge button on homescreen and once they begin the recharge journey, the number of screens causes cognitive load, causing frustration. Lack of progress status bar generates uncertainty and impatience on the recharge journey. Frequent yet one-way commuters also require a micro-recharge of ₹50 as a quick suggestion option.&nbsp;</p>
<h2>Solutions&nbsp;</h2>
<p>Out of the solutions brainstormed for all three personas, then boiling it down to the common&nbsp;</p>
<h3><strong>Proposed Solutions&nbsp;</strong></h3>
<ul>
<li>Improved recharge icon visibility in homepage</li>
<li>Reducing the amount of screens to curb slow loading/screen freezing&nbsp;</li>
<li>Low balance push notifications&nbsp;</li>
<li>Micro recharge quick suggestions for one-way travel&nbsp;</li>
<li>Payment status bar on top to show remaining steps&nbsp;</li>
<li>Auto-payment triggers and push notification reminders&nbsp;</li>
<li>NFC top-up CTA immediately after successful recharge</li>
</ul>
<h3><strong>Solution Prioritization&nbsp;</strong></h3>
<p>Using the MoSCoW Prioritization Technique, we will analyse the business objectives, design infrastructure, and the engineering costs to prioritise the solutions required to implement in the UX redesign of the app:&nbsp;</p>
<table>
<tbody>
<tr>
<td>
<p>MoSCoW Analysis&nbsp;</p>
</td>
<td>
<p>Suggested Solutions&nbsp;</p>
</td>
<td>
<p>Business Objective&nbsp;</p>
</td>
<td>
<p>UX/Design Requirement&nbsp;</p>
</td>
<td>
<p>Engineering Costs</p>
</td>
<td>
<p>Reasoning&nbsp;</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>Must have (M)</p>
</td>
<td>
<p>Improved recharge icon visibility in homepage</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Low&nbsp;</p>
</td>
<td>
<p>User Impact: High, users will swift through the icon to complete easy transaction&nbsp;</p>
<p>Confidence: High, the more the icon stands out, better the performance and higher customer satisfaction&nbsp;</p>
<p>Implementation Dependencies: Low, minimal design and tech requirements for the icon redesign&nbsp;</p>
<p>Operational Risk: Low, lowest chances of app abandonment due to reduction in median transaction time&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Reducing the amount of screens to curb slow loading/screen freezing</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>User Impact: High, with customer satisfaction on ease of transaction process&nbsp;</p>
<p>Confidence: Medium, with users interacting with least screens possible, completing the transaction in minimum time required</p>
<p>Implementation Dependencies: Low on tech and design&nbsp;</p>
<p>Operational Risk: Low, with confidence on user adoption&nbsp;</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>Should have (S)</p>
</td>
<td>
<p>Micro recharge quick suggestions for one-way travel</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Low&nbsp;</p>
</td>
<td>
<p>User Impact: high, for the students getting one-way transaction amenities quickly</p>
<p>Confidence: high, with all users getting a chance to complete micro-transactions&nbsp;</p>
<p>Implementation Dependencies: Low on tech and design&nbsp;</p>
<p>Operational Risk: Low chances of drop-off due to feature addition&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Payment status bar on top to show remaining steps</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Low&nbsp;</p>
</td>
<td>
<p>User Impact: High, feature is eligible for the pain points of users of all personas&nbsp;</p>
<p>Confidence: High, adoption into the payments process helps ease the transaction anxiety&nbsp;</p>
<p>Implementation Dependencies: Medium for design and engineering&nbsp;</p>
<p>Operational Risk: Low, with confidence on high adoption&nbsp;</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>Could have (C)</p>
</td>
<td>
<p>NFC top-up CTA immediately after successful recharge</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>User Impact: Medium, tech-savvy users will find the entire recharge process time efficient&nbsp;</p>
<p>Confidence: Medium, removing the mobile readability and other tech drawbacks, the user will find the solution helpful&nbsp;</p>
<p>Implementation Dependencies: Medium, with required tech and design requirements and regular maintenance&nbsp;</p>
<p>Operational Risk: Medium, the network connectivity must be of minimum threshold to complete NFC top-up duly after successful recharge</p>
</td>
</tr>
<tr>
<td>
<p>Low balance push notifications</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Low&nbsp;</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>User Impact: Medium, notification frequency should be phased out once the balance reaches the minimum threshold&nbsp;</p>
<p>Confidence: Low, useful in few cases, users might turn off notifications if categories as spam</p>
<p>Implementation Dependencies: Medium, high tech requirements&nbsp;</p>
<p>Operational Risk: Medium, users might turn off notifications, causing overall disadvantage to other services&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Won&rsquo;t have (W)</p>
</td>
<td>
<p>Auto-payment triggers and push notification reminders</p>
</td>
<td>
<p>Medium&nbsp;</p>
</td>
<td>
<p>Low&nbsp;</p>
</td>
<td>
<p>High&nbsp;</p>
</td>
<td>
<p>User Impact: Medium, the users who have activated the option will be notified in advance if they wish to opt out&nbsp;</p>
<p>Confidence: High, the transactions will be completed efficiently in a predetermined manner&nbsp;</p>
<p>Implementation Dependencies: High, tech requirements must align with the GTM approach and users must not flag the notifications as spam&nbsp;</p>
<p>Operational Risk: Medium, phased out notifications to be released once the minimum limit threshold is reached</p>
</td>
</tr>
</tbody>
</table>
<p>The selected are relevant to all personas, as well as require minimal budget costs. The focus is on designing the features and tweaking the UX for a better, streamlined transaction process.&nbsp;</p>
<h2>MVP Solution Design Prototype&nbsp;</h2>
<p><strong><a href="https://www.figma.com/design/Le6nZ26Cj8DocknDJQYf99/Airtel-Payments-Bank-NCMC--Wireframe-?node-id=0-1&amp;t=GdkWOKlwj7hH2kd4-0">Airtel Payments Bank NCMC (Wireframe)</a>&nbsp;</strong></p>
<p><strong><a href="https://www.figma.com/proto/Le6nZ26Cj8DocknDJQYf99/Airtel-Payments-Bank-NCMC?node-id=187-2197&amp;t=2cbYll0f9TIUjDFo-0&amp;scaling=scale-down&amp;content-scaling=fixed&amp;page-id=176%3A2&amp;starting-point-node-id=176%3A3">Airtel Thanks App - Mobile App</a></strong>&nbsp;</p>
<h2>Defining Success Metrics&nbsp;</h2>
<h3><strong>North Star/ Primary Metrics</strong></h3>
<p>To curb the total number of successful recharge completions and curb the drop-off rate by decreasing the time required to complete the payment process of the regular and occasional users.&nbsp;</p>
<h3><strong>Secondary Metrics&nbsp;</strong></h3>
<ul>
<li>Reducing customer dissatisfaction&nbsp;</li>
<li>Keep customers from leaving before completing transaction&nbsp;</li>
<li>Increase returning users&nbsp;</li>
<li>Keep up with the competitor UPI TRAPs</li>
</ul>
<table>
<tbody>
<tr>
<td>
<p>Metrics&nbsp;</p>
</td>
<td>
<p>KPIs</p>
</td>
<td>
<p>OKRs&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Reducing customer dissatisfaction&nbsp;</p>
</td>
<td>
<p>Reducing Drop Off Rate&nbsp;</p>
</td>
<td>
<p>Objective: Simplify the payment process by reducing the no. of screens the users interact with&nbsp;</p>
<p>Key Results: Median time reduced to 35% in completing the transaction after redesign&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Keep customers from leaving before completing transaction&nbsp;</p>
</td>
<td>
<p>Reduce Churn Rate</p>
</td>
<td>
<p>Objective: Show payment progress bar to keep the user informed&nbsp;</p>
<p>Key Results: 80% payments are completed in one go&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p>Increase returning users&nbsp;</p>
</td>
<td>
<p>Increase Retention Rate</p>
</td>
<td>
<p>Objective: Retouch UI and reduce information overwhelming&nbsp;</p>
<p>Key Results: Increase in returning users due to simplified procedure, improve post-recharge card synchronization</p>
</td>
</tr>
<tr>
<td>
<p>Keep up with the competitor UPI TRAPs</p>
</td>
<td>
<p>Rediscover Product-Market Fit&nbsp;</p>
</td>
<td>
<p>Objective: Introduce micro-recharges of minimum ₹50, as offered by competitor DMRC Saarthi App for their smart QR recharges, for one-way commutes</p>
<p>Key Results: Increase app MAU for secured, frequent short travels&nbsp;</p>
</td>
</tr>
</tbody>
</table>
<h3><strong>Guardrail Metrics</strong></h3>
<ul>
<li>Turnstile Tap Latency for offline payments top-up processing to guard the security system&nbsp;</li>
<li>Slow Card Synchronisation or Errors in Processing Payments instantly due to technical delays and/or mismatches</li>
</ul>
<h2>Key Takeaways as a PM</h2>
<p>As an aspiring APM/PM 1, these are the key takeaways from the Airtel thanks app teardown:</p>
<ul>
<li>Brainstorm but prioritise with evidence and logic</li>
<li>Do not jeopardize revenue for advanced features</li>
<li>Design and test with real users of the persona demographic for further iterations&nbsp;</li>
<li>Document the progress and observations&nbsp;</li>
</ul>
<p>Appreciate your time and efforts to read, please do reach out for any recommendations, observations, feedback, or just a casual coffee chat!</p>
