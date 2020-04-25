<h2 align="center">
	Trigger in DynamoDB
</h2>
<p align="center">
Firing a trigger created in a <b>lambda</b> function when inserting documents in <b>DynamoDB</b> by means of a stream, using <b>decorator</b> for customized validations. And everything being made available through the <b>Serverless Framework</b>.
</p>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/robertosousa1/trigger-dynamodb.svg">
  
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/robertosousa1/trigger-dynamodb.svg">
  
  <a href="https://www.codacy.com/app/robertosousa1/trigger-dynamodb?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=robertosousa1/trigger-dynamodb&amp;utm_campaign=Badge_Grade">
  </a>
  
  <a href="https://github.com/robertosousa1/trigger-dynamodb/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/robertosousa1/trigger-dynamodb.svg">
  </a>
  
  <a href="https://github.com/robertosousa1/trigger-dynamodb/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/robertosousa1/trigger-dynamodb.svg">
  </a>
</p>

<p align="center">
<a href="#rocket-technology">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ballot_box_with_check-prerequisites">Prerequisites</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#up-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#pencil2-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## [](#technology):rocket: Technology
-  **[AWS Lambda](https://aws.amazon.com/pt/lambda/)** — Allows you to run code without provisioning or managing servers.
- **[AWS DynamoDB](https://aws.amazon.com/pt/dynamodb/)** — Fully managed NoSQL database service that supports key-value data structures and documents.
- **[Serverless Framework](https://serverless.com/)** — Gives you everything you need to develop, deploy, monitor and secure serverless applications on any cloud.


## [](#prerequisites):ballot_box_with_check: Prerequisites
-   [Node.js](https://nodejs.org/en/)
-   [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/pt-BR/docs/install)
- [AWS CLI](https://aws.amazon.com/pt/cli/)
- [Serverless Framework](https://serverless.com/)

## [](#getting-started):up: Getting started

-   Clone this repo
-  Enter the folder `trigger-dynamodb`
-  Run `yarn` or `npm install` to install the dependencies
- Run `sls deploy` or `serverless deploy` to upload the lambda function to AWS
- Run `invoke-insert` to perform a data entry function in DynamoDB
- Run `logs-trigger` to view the trigger log
## [](#how-to-contribute):pencil2: How to contribute

-   Make a fork;
-   Create a branck with your feature:  `git checkout -b my-feature`;
-   Commit changes:  `git commit -m 'feat: My new feature'`;
-   Make a push to your branch:  `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## [](#license):memo: License
This project is under the MIT license. See the [LICENSE](https://github.com/robertosousa1/trigger-dynamodb/blob/master/LICENSE) for more information.

----------

Made with by Roberto Sousa  👋  [Get in touch!](https://www.linkedin.com/in/robertosousa01/)


