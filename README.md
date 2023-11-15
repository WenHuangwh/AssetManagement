# AssetManagement

## Introduction
AssetManagement is a web application designed for investment companies to manage their assets efficiently. This app offers comprehensive features for handling various asset classes, managing portfolios, and ensuring robust security.

## Features

### P0 - Essential Features
These features are crucial for the basic functionality of the app.

- As an investment manager, I want to create a account for asset management.
- As an investment manager, I want to register all my current assets into the system. Each asset should have a purchase date, purchase price, volume, end date(duration)(optional), balance sheet class(optional, like hold to maturity, available for sale).
- As an investment manager, I want to add money to my account. (We should store asset price each time new cash flow in/out to the account for return calculation)
- As an investment manager, I want to find/register any asset. For public listed asset like stock, bond, mutual fund, the system should find information for me; for alternative asset like real estate, bank checking/saving account, I can register information for this asset.
- As an investment manager, I want to register my transaction of assets in my account. (stock -> stock, cash -> stock, stock -> bond)
- As an investment manager, I want to view my balance sheet of given time.
- As an investment manager, I want to get my asset return of any given time period.
- As a portfolio manager, I want to compare investment manager's performance with bench mark.
- As a portfolio manager, I want to know asset weight broken down by asset class, industry, country.
- As a risk manager, I want to know risk factor like alpha, beta, standard deviation of portfolio.
- As a risk manager, I want to do monte-carlo simulation on current portfolio.
- As a head of investment, I want to see all transaction of given period.
- As a head of investment, I want to see company's asset in one portfolio.

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

# Frontend

## Frontend Framework

### React
We have chosen React as our primary frontend framework due to its component-based architecture and widespread adoption, which is ideal for building dynamic and data-intensive user interfaces.

### Optional Framework Extensions
Additional frameworks may be utilized as extensions to React based on specific project requirements.

## Data Fetching

- **RESTful API**: Suitable for straightforward data requirements. We will use RESTful APIs for their simplicity and wide compatibility.
- **GraphQL**: Considered for more complex, nested data requirements where minimizing data over-fetching is crucial.

## UI Frameworks

We are considering the following UI frameworks:
- **React-Bootstrap**: Optimal for rapid development with familiar and responsive design components.
- **Material UI**: Offers a comprehensive set of components with material design principles.
- **Ant Design**: Known for its enterprise-level component library and design system.

## Libraries for Metrics and Timeline Data

### Charting Libraries
- **Recharts**: A composable charting library built on React components, known for its simplicity and customizability.
- **Chart.js**: A popular library for interactive charts, easily integrated into React with `react-chartjs-2`.

### Data Grid Libraries
- **ag-Grid**: Provides a rich feature set for displaying complex data sets, including integrated charting, sorting, and filtering.
- **Material-UI DataGrid**: An effective choice within the Material-UI ecosystem for handling large data sets.

### Timeline Libraries
- **React Calendar Timeline**: Specialized for creating timelines in React, offering customizability and drag-and-drop support.
- **vis.js**: A dynamic visualization library with a capable Timeline component for horizontal timeline displays.

## Decision Summary
- We will use **React-Bootstrap** for the UI framework as uniqueness in UI design is not a primary concern.
- **RESTful APIs** will be our default choice for data fetching, given the current project scope doesn't demand complex data fetching.
- Integration of charting, data grid, and timeline libraries will be further discussed and decided as we progress in implementing specific pages.

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

