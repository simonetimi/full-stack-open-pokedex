## CI + PHP

- Before deploying a build with PHP, there are some tools that might help us with CI.
  Style checking is important to keep all the code consistent, even when working with other developers. PHP code sniffer is a nice tool that helps us indentations, unused variables and naming conventions, just like Eslint for JavaScript.
  Testing is also an important part of the CI process. For PHP, PHPUnit allow to do unit testing easily. After writing my tests, the software will generate a log with the errors and the tests that run.
  Checking for vulnerabilities is also an important part of the process. For PHP, we can using SensioLabs to scan our code and check if it contains vulnerabilities (e.g. vulnerable dependencies) that malicious users could exploit.

- CI can be done using mul tiple tools, such as Jenkins or GitHub actions. Other platforms include: Azure Pipelines, CircleCI, Gitlab or Travis CI. Gitlab seems pretty popular on the web.

- Choosing self-hosted or cloud-based environments boils down to the complexity of the set-up and the price. If my project doesn't require frequent deployments and doesn't have special needs, then I'd go for a cloud-based environment. If my problem would require really frequent actions, then a solution where you pay for the server itself rather than the time the servers spends executing those actions might be preferable (self-hosted).
