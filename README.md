## Deploy simple web page showing Amazon Q Embedded 

Run the simplewebpageDeploy YML file from CloudFormation.
When prompted enter a unique Stack name, a name for the website and the Q Business application ID.

## When stack has completed
Navigate to the Outputs tab for this stack. Make a note of the AmplifyAppUrl URL, we will need to add this to the allowed websites that can use Q Assistant.
In the AWS console, head to the Amazon Q Business page. On the left panel click on Applications.
Select your application and click on Embed Amazon Q Business found on the left side of the page.
Click on the Add allowed website button to add website. Enter the URL you made a note of here and save.
Finally open this URL in your browser. This will bring up the webpage we just deployed
containing the embeddable widget for Q Business.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

