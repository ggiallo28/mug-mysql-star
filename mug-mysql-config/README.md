# MuG::MySQL::Config

Congratulations on starting development!

Next steps:

1. Populate the JSON schema describing your resource, `mug-mysql-config.json`
2. The RPDK will automatically generate the correct resource model from the
   schema whenever the project is built via Make.
   You can also do this manually with the following command: `cfn-cli generate`
3. Implement your resource handlers by adding code to provision your resources in your resource handler's methods.

Please don't modify files `model.go and main.go`, as they will be automatically overwritten.

python3.7 -m venv cfn_go_plugin
source cfn_go_plugin/bin/activate
pip install cloudformation-cli==0.1.12 cloudformation-cli-go-plugin==2.0.2

sam local start-lambda

https://medium.com/@vissree/cloudformation-private-resource-provider-for-github-webhooks-1f38f42cbf72