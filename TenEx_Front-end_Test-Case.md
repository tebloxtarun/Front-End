

### **Homepage**

| **Test Case ID** | **Description**          | **Steps**                                                                                       | **Expected Output**                                               | **Passed** | **Failed** |
|------------------|--------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|------------|------------|
| 1.1              | Verify Navigation Links  | 1. Open the homepage. <br> 2. Click on each navigation link (e.g., Home, About, Services, Contact). | The user is redirected to the correct page.                       |            |            |
| 1.2              | Verify Banner Display    | 1. Open the homepage. <br> 2. Check the banner section for announcements and updates.              | Banners are displayed correctly and update as expected.           |            |            |
| 1.3              | Verify Responsive Design | 1. Open the homepage on various devices (desktop, tablet, mobile) and screen sizes.              | The homepage displays correctly on all devices and screen sizes.  |            |            |

### **Wallet Integration**

| **Test Case ID** | **Description**                 | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|---------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 2.1              | Connect Wallet                  | 1. Click on the "Connect Wallet" button. <br> 2. Select a wallet (e.g., MetaMask) and follow the prompts to connect.        | The wallet connects successfully, and the user’s balance is displayed. |            |            |
| 2.2              | Disconnect Wallet               | 1. Click on the "Disconnect Wallet" button.                                                                              | The wallet disconnects successfully.                                |            |            |
| 2.3              | Verify Wallet Balance Display   | 1. Connect a wallet. <br> 2. Check the displayed balance on the dashboard.                                                 | The wallet balance displays correctly.                              |            |            |
| 2.4              | Verify Transaction Confirmation | 1. Initiate a transaction (e.g., swap tokens). <br> 2. Confirm the transaction through the wallet prompt.                   | The transaction is confirmed and processed correctly.               |            |            |
| 2.5              | Verify Network Switching Prompt | 1. Connect a wallet that is on the wrong network.                                                                        | The DEX prompts the user to switch to the correct network.          |            |            |

### **Dashboard**

| **Test Case ID** | **Description**                 | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|---------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 3.1              | Verify Dashboard Navigation     | 1. Navigate through different sections of the dashboard (e.g., Overview, Transactions, Settings).                        | Each section loads correctly.                                       |            |            |
| 3.2              | Verify Notifications Display    | 1. Perform actions that trigger notifications (e.g., successful trades, staking rewards). <br> 2. Check the notifications section. | Notifications appear correctly.                                     |            |            |

### **Trading Interface**

| **Test Case ID** | **Description**                   | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 4.1              | Verify Token Selection            | 1. Open the trading interface. <br> 2. Select different tokens from the dropdown menu.                                     | Tokens are selected correctly.                                      |            |            |
| 4.2              | Verify Real-Time Price Updates    | 1. Open the trading interface. <br> 2. Monitor the price updates for the selected tokens.                                  | Prices update in real-time.                                         |            |            |
| 4.3              | Verify Order Placement            | 1. Open the trading interface. <br> 2. Place a buy/sell order by entering the amount and price. <br> 3. Confirm the order.   | Orders are placed successfully.                                     |            |            |
| 4.4              | Verify Order Book Accuracy        | 1. Open the trading interface. <br> 2. Check the order book for the selected trading pair.                                 | The order book displays accurate information.                       |            |            |
| 4.5              | Verify Transaction History Display | 1. Open the transaction history section. <br> 2. Check the history after placing orders.                                   | Transaction history is displayed correctly.                         |            |            |

### **Liquidity Pools**

| **Test Case ID** | **Description**                   | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 5.1              | Verify Adding Liquidity           | 1. Navigate to the liquidity pools section. <br> 2. Select a pool. <br> 3. Enter the amount to add. <br> 4. Confirm the transaction. | Liquidity is added successfully.                                    |            |            |
| 5.2              | Verify Removing Liquidity         | 1. Navigate to the liquidity pools section. <br> 2. Select a pool. <br> 3. Enter the amount to remove. <br> 4. Confirm the transaction. | Liquidity is removed successfully, and tokens are received.         |            |            |
| 5.3              | Verify Pool Details Display       | 1. Navigate to the liquidity pools section. <br> 2. Check the details of a selected liquidity pool, including APR, volume, and other relevant information. | Pool details, including APR and volume, are accurate.               |            |            |
| 5.4              | Verify Gauge Voting               | 1. Navigate to the gauge voting section. <br> 2. Vote on liquidity gauges by selecting the preferred option and confirming the vote. | Votes are recorded and affect rewards distribution.                 |            |            |

### **Staking**

| **Test Case ID** | **Description**                   | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 6.1              | Verify Staking Tokens             | 1. Navigate to the staking section. <br> 2. Select a staking pool. <br> 3. Enter the amount to stake. <br> 4. Confirm the transaction. | Tokens are staked successfully.                                     |            |            |
| 6.2              | Verify Unstaking Tokens           | 1. Navigate to the staking section. <br> 2. Select a staking pool. <br> 3. Enter the amount to unstake. <br> 4. Confirm the transaction. | Tokens are unstaked successfully, and rewards are received.         |            |            |
| 6.3              | Verify Rewards Display            | 1. Navigate to the staking section. <br> 2. Check the rewards section.                                                     | Rewards are displayed correctly and update in real-time.            |            |            |
| 6.4              | Verify Voting Escrow Rewards      | 1. Navigate to the rewards section. <br> 2. Check the rewards based on ve(3,3) votes.                                      | Additional rewards are received based on votes.                     |            |            |

### **Governance**

| **Test Case ID** | **Description**                   | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 7.1              | Verify Voting on Proposals        | 1. Navigate to the governance section. <br> 2. Select a proposal. <br> 3. Vote by choosing an option and confirming the vote. | Votes are recorded and counted correctly.                           |            |            |
| 7.2              | Verify Proposal Creation          | 1. Navigate to the governance section. <br> 2. Create a new proposal by filling in the required details and submitting it.  | Proposal is created successfully.                                   |            |            |
| 7.3              | Verify Proposal Details Display   | 1. Navigate to the governance section. <br> 2. Check the details of a selected proposal, including votes and outcomes.      | Proposal details, including votes and outcomes, are displayed correctly. |            |            |
| 7.4              | Verify Bribe Functionality        | 1. Navigate to the bribe section. <br> 2. Offer a bribe for voting incentives by entering the amount and confirming the transaction. | Bribe is recorded and affects voting incentives.                    |            |            |

### **Notifications**

| **Test Case ID** | **Description**                   | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 8.1              | Verify Real-Time Notifications    | 1. Perform actions that trigger notifications (e.g., successful trades, staking rewards). <br> 2. Check the notifications section. | Notifications are received in real-time.                            |            |            |
| 8.2              | Verify Read/Unread Status         | 1. Navigate to the notifications section. <br> 2. Mark notifications as

 read/unread.                                      | Notifications status updates correctly.                             |            |            |

### **Error Handling**

| **Test Case ID** | **Description**                               | **Steps**                                                                                                                                               | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 9.1              | Verify Behavior Under Poor Network Conditions | 1. Simulate poor network conditions (e.g., slow internet connection). <br> 2. Perform various actions (e.g., placing orders, connecting wallet).           | Appropriate error messages are displayed.                           |            |            |
| 9.2              | Verify Server Error Messages                  | 1. Simulate server errors by disconnecting the server or causing server issues. <br> 2. Perform various actions (e.g., placing orders, staking tokens).   | Appropriate error messages are displayed.                           |            |            |

### **Performance Testing**

| **Test Case ID** | **Description**                  | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|----------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 10.1             | Verify Page Load Times           | 1. Measure load times for all pages using tools like Google PageSpeed Insights or GTmetrix.                              | Load times are within acceptable limits.                            |            |            |
| 10.2             | Verify Front-End Under High User Load | 1. Simulate high user load conditions using load testing tools (e.g., JMeter). <br> 2. Monitor the performance of the front-end. | The front-end performs well without significant slowdowns.          |            |            |

### **Security Testing**

| **Test Case ID** | **Description**                        | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 11.1             | Verify XSS Protection                  | 1. Attempt to inject malicious scripts into input fields (e.g., forms, search bars).                                      | Scripts are sanitized and not executed.                             |            |            |
| 11.2             | Verify CSRF Protection                 | 1. Attempt Cross-Site Request Forgery (CSRF) attacks using CSRF tools or manual methods. <br> 2. Perform various actions (e.g., form submissions). | CSRF protections prevent the attack.                                |            |            |
| 11.3             | Verify Data Encryption                 | 1. Check the transmission of sensitive data (e.g., login credentials, transaction details) using network monitoring tools. | Data is encrypted during transmission.                              |            |            |

### **Cross-Browser Testing**

| **Test Case ID** | **Description**                        | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 12.1             | Verify Browser Compatibility           | 1. Test the front-end on various browsers (Chrome, Firefox, Safari, Edge).                                               | The front-end works correctly on all browsers.                      |            |            |
| 12.2             | Verify Version Compatibility           | 1. Test the front-end on different versions of the browsers (latest and one or two previous versions).                    | The front-end works correctly on all tested versions.               |            |            |

### **Accessibility Testing**

| **Test Case ID** | **Description**                        | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 13.1             | Verify Screen Reader Compatibility     | 1. Use a screen reader (e.g., JAWS, NVDA) to navigate the site. <br> 2. Check if all interactive elements are accessible.    | The site is fully navigable with a screen reader.                    |            |            |
| 13.2             | Verify Keyboard Navigation             | 1. Navigate the site using only a keyboard. <br> 2. Ensure all interactive elements can be accessed and used.                | The site is fully navigable via keyboard.                           |            |            |
| 13.3             | Verify Color Contrast                  | 1. Check color contrast using tools like the WCAG Contrast Checker. <br> 2. Ensure text and interactive elements are readable. | The site meets color contrast standards for readability.            |            |            |

### **Integration Testing**

| **Test Case ID** | **Description**                        | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 14.1             | Verify API Integration                 | 1. Test interactions with backend APIs (e.g., retrieving data, submitting forms). <br> 2. Ensure the front-end handles responses correctly. | APIs respond correctly and the front-end handles the responses appropriately. |            |            |
| 14.2             | Verify External Services Integration   | 1. Test integration with external services (e.g., wallet providers, price oracles). <br> 2. Ensure data from these services is handled correctly. | The front-end integrates seamlessly with external services.         |            |            |

### **User Feedback**

| **Test Case ID** | **Description**                        | **Steps**                                                                                                                | **Expected Output**                                                 | **Passed** | **Failed** |
|------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|------------|
| 15.1             | Verify Feedback Form Submission        | 1. Navigate to the feedback form. <br> 2. Fill out the form and submit feedback.                                            | Feedback is logged correctly.                                       |            |            |
| 15.2             | Verify Bug Reporting Feature           | 1. Navigate to the bug reporting feature. <br> 2. Submit a bug report.                                                      | The bug report is submitted successfully.                           |            |            |
