# Tyk Training Deployment
CloudFormation templates for students to deploy Tyk on EC2
You may refer to this repository during and after training session to study and revise techniques used in the training session.

CloudFormation templates will deploy each Tyk component standalone in separate EC2 instances. 

1. Choose the OS that you would like to deploy Tyk on.
2. Create a key-pair on AWS Dashboard > EC2 > Key-Pair
3. Add key-pair name in CloudFormation template in Parameters > KeyName > Default
4. Deploy CloudFormation template on AWS Dashboard
5. Access the public URL of the Dashboard and add in the license key into the text field.
6. Bootstrap the deployment (add in organisation name and admin user details)

Workshop 1: Foundational Tyk Usage
- Creating an API: https://tyk.io/docs/getting-started/create-api/#tutorial-create-an-api-with-the-dashboard
- Securing an API: https://tyk.io/docs/getting-started/create-security-policy/#tutorial-create-a-security-policy-with-the-dashboard
- Accessing an API: https://tyk.io/docs/getting-started/create-api-key/#tutorial-create-an-api-key-with-the-dashboard

Workshop 2: Analytics
- Traffic Overview: https://tyk.io/docs/tyk-dashboard-analytics/traffic-overview/
- Traffic per API: https://tyk.io/docs/tyk-dashboard-analytics/traffic-per-api/
- Traffic per Key: https://tyk.io/docs/tyk-dashboard-analytics/traffic-per-token/
- Log Browser: https://tyk.io/docs/tyk-stack/tyk-manager/analytics/log-browser/

Workshop 3: Endpoint Designer
- Transform JSON & XML: https://tyk.io/docs/advanced-configuration/transform-traffic/soap-rest/
- Virtual Endpoint: https://tyk.io/docs/advanced-configuration/compose-apis/demo-virtual-endpoint/

Workshop 4: Retrieving logs, configuration files and setting logging verbosity
- Refer to text document 'workshop4.txt'

Workshop 5: Using psql/mongosh and redis-cli
- Refer to text document 'workshop5.txt'

Workshop 6: Tyk Sync

Workshop 7: Upgrading Tyk
- Refer to text document 'workshop7.txt'
