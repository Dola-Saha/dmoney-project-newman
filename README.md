# DMoney Newman API Test Project

## Project Summary

This project automates API testing for the DMoney application using a Postman collection executed with Newman. The collection covers DMoney workflows such as admin authentication, user management, and transaction-related API requests. Test results are exported as an HTML report.

## Technologies

- Node.js and npm
- Newman 6
- Postman Collection v2.1
- Newman HTML Extra Reporter
- JavaScript

## Prerequisites

- Node.js and npm installed
- Git installed
- The DMoney API running at `http://localhost:5000`

## Clone the Project

Replace `<repository-url>` with the URL of this repository:

```bash
git clone <repository-url>
cd DMONEY-PROJECT-NEWMAN
```

## Install Dependencies

```bash
npm install
```

This installs the Newman packages defined in `package.json`.

## Run the Tests

Start the DMoney API on port `5000`, then run:

```bash
npm test
```

The command runs the collection once through `report.js`. When execution completes, the HTML report is available at:

```text
Reports/report.html
```

## Project Structure

```text
collection/dmoney-project1.json  Postman API test collection
report.js                         Newman test runner configuration
Reports/report.html               Generated HTML test report
package.json                      Project metadata and scripts
```
