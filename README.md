# CDK Snippets for Python
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/sameeramin.cdk-snippets-for-python)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/sameeramin.cdk-snippets-for-python)
![Visual Studio Marketplace Rating (Stars)](https://img.shields.io/visual-studio-marketplace/stars/sameeramin.cdk-snippets-for-python)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/sameeramin/cdk-snippets-for-python/ci.yml)
![GitHub issues](https://img.shields.io/github/issues-raw/sameeramin/cdk-snippets-for-python)

**CDK Snippets for Python** is an extension for the Visual Studio Code editor that provides code snippets for creating various components of an AWS service, such as REST APIs, resources, methods, integrations, models, and authorizers. The snippets are written in Python and are designed to be used with the AWS CDK library for defining cloud resources.

This extension is a great tool for developers who are working with AWS services and the AWS CDK library. It makes it easy to create and manage AWS resources with minimal code and effort, allowing developers to focus on building their applications.

![CDK Snippets for Python Tutorial](./docs/images/tutorial.gif)

## Inspiration
This extension was inspired by the need to simplify the process of creating an AWS service. The AWS Cloud Development Kit (CDK) is a powerful tool for defining cloud resources, but the process of writing the code for creating an AWS service can be time-consuming and error-prone. The goal of this extension is to provide a convenient way to generate the boilerplate code needed to set up an AWS service, reducing the time and effort required to manually write the code.

This project is also inspired by [Dr. Ayesha Ashfaq](https://www.linkedin.com/in/ayesha-binte-a-90755b8/) who has been doing a great job at [SkipQ](https://skipq.org/) by making young graduates job ready by conducting extensive and fun training and shortening the gap between industry and academia. Her encouragement and guidance motivated me to contribute to open-source projects and make a positive impact on the developer community.


## Features:

- The extension provides code snippets for creating various components of an AWS service, such as REST APIs, resources, methods, integrations, models, and authorizers.
- The snippets are written in Python and are designed to be used with the AWS CDK library for defining cloud resources.
- he extension also includes code snippets for creating different types of authorizers, such as token and request authorizers.
- It also has code snippets for creating different types of API definition, such as Asset, S3 and Inline API definition.
- The extension provides a convenient way to generate the boilerplate code needed to set up an AWS service, reducing the time and effort required to manually write the code.
- The extension also includes a description of each snippet, making it easy to understand their purpose and usage.
- It also has placeholders and tab stops which can help you to easily fill the required inputs.
- It also provides a prefix for each snippet which can be easily triggered by writing the prefix in the editor and pressing tab.


## Installation

1. Open VS Code
2. Press `CTRL + SHIFT + X` (or `CMD + SHIFT + X` on Mac) to open the Extensions pane
3. Search for "cdk snippents for python"
4. Click the install button
5. Reload VS Code


## Usage
Once the extension is installed and activated, you can use the code snippets by typing the prefix of the snippet you want to use and then pressing TAB. For example, to use the AWS API Gateway service's REST API code snippet, you can type `apigw-rest-api` and then press TAB. The snippet will be inserted into the editor.

## Available Snippets
- `s3`: Creates an S3 bucket
- `codebuild`: Creates a CodeBuild project
- `codepipeline`: Creates a CodePipeline
- `rds`: Creates an RDS instance
- `ec2`: Creates an EC2 instance
- `cloudfront`: Creates a CloudFront distribution

And more...
Click [here](./CATALOG.md) to know more about available snippets.
## Feature Request

If you have a feature request or an issue, please head over to issues on [GitHub](https://github.com/sameeramin/cdk-snippets-for-python/issues).


## Contributing
You're welcome to contribute to this project by adding more snippets or fixing existing ones.

## Authors
[Muhammad Sameer](https://github.com/sameeramin), [Ayesha Goheer](https://github.com/AyeshaGoheer)

## License
This extension is under the [MIT](https://choosealicense.com/licenses/mit/) license.

## Disclaimer
This extension is not affiliated with Amazon Web Services.
