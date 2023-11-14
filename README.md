# AssetManagement

## Introduction
AssetManagement is a web application designed for investment companies to manage their assets efficiently. This app offers comprehensive features for handling various asset classes, managing portfolios, and ensuring robust security.

## Features

### P0 - Essential Features
These features are crucial for the basic functionality of the app.

- **Manage Portfolios**:
  - Investment Company: Manage individual and combined portfolios for each manager and department.
- **Asset Classes**:
  - Investment Company: Incorporate various asset classes like cash, bonds, and stocks.
- **Asset Categorization**:
  - Account Manager: Categorize assets (HTM, AFS, trading).
- **Cash Management**:
  - Investment Company: Inject new cash into company account and allocate to investment managers.
- **Transaction Requests**:
  - Investment Manager: Submit transaction requests to traders.
  - Trader: Initiate and execute trade requests.
- **Logging and Recording**:
  - Investment Company: Log all managers’ requests and traders’ transactions.
- **Real-time Balances**:
  - Investment Company: View real-time balances of managers, teams, and the company.
- **Security and Backup**:
  - IT Administrator: Implement robust security and data backup features.
- **Profit and Loss Statements**:
  - Account Manager: Access to real-time profit and loss statements.

### P1 - High Value Features
These features add significant value and should be included in the early development stages.

- **Research and Reports**:
  - Research Analyst: Upload and associate reports with assets.
  - Investment Manager: Search for reports.
- **Risk Management Tools**:
  - Risk Manager: Tools to assess total beta, duration, std, and theta of products and portfolio.
- **Portfolio Insights**:
  - Portfolio Manager: Insights into asset and industry weight distribution and benchmark comparisons.

### P2 - Enhancement Features
These features enhance user experience and can be developed in later phases.

- **Client Portal**:
  - Client Relationship Manager: Client-facing portal for portfolio performance.
- **HR Integration**:
  - HR Manager: Integration with HR systems for performance metrics.
- **Audit and Control**:
  - Audit and Control: Audit trails and control mechanisms.
- **Market Analysis**:
  - Marketing Manager: Analyze investment trends and client preferences.

Frontend(client): 1.Framework(React(single page), Next.js(complicate), ...); 2.UI design pattern; 3.Restful(90%)/GraphQL/MVC(fast, hard)

React    -netwrok json http ip tcp socket- (Restful Api, AJAX, GraphQL)  Spring/Django/Node.js
html,js,views,dao Django

browser -> React(AWS) -> Spring1(Azure) -> Spring2 -> Spring3 -> Spring4 -> SQL(oracle)
browser -> Django(Azure) -> SQL(oracle)

Stock: buy price, volumn, date,
Backend(server): Spring, Django, Node.js, pandas/numpy/pytorch, Finance data API(free)

Database: SQL/Non-SQL, PostgreSQL, MySQL, deploy platform

## Contributing
We welcome contributions from the community. Please read our contributing guidelines before submitting your pull requests.

