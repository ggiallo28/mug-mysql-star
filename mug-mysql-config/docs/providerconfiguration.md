# MuG::MySQL::Config ProviderConfiguration

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "<a href="#endpoint" title="Endpoint">Endpoint</a>" : <i>String</i>,
    "<a href="#username" title="Username">Username</a>" : <i>String</i>,
    "<a href="#password" title="Password">Password</a>" : <i>String</i>,
    "<a href="#proxy" title="Proxy">Proxy</a>" : <i>String</i>,
    "<a href="#tls" title="TLS">TLS</a>" : <i>String</i>,
    "<a href="#maxconnlifetimesec" title="MaxConnLifetimeSec">MaxConnLifetimeSec</a>" : <i>Integer</i>,
    "<a href="#maxopenconns" title="MaxOpenConns">MaxOpenConns</a>" : <i>Integer</i>,
    "<a href="#authenticationplugin" title="AuthenticationPlugin">AuthenticationPlugin</a>" : <i>String</i>
}
</pre>

### YAML

<pre>
<a href="#endpoint" title="Endpoint">Endpoint</a>: <i>String</i>
<a href="#username" title="Username">Username</a>: <i>String</i>
<a href="#password" title="Password">Password</a>: <i>String</i>
<a href="#proxy" title="Proxy">Proxy</a>: <i>String</i>
<a href="#tls" title="TLS">TLS</a>: <i>String</i>
<a href="#maxconnlifetimesec" title="MaxConnLifetimeSec">MaxConnLifetimeSec</a>: <i>Integer</i>
<a href="#maxopenconns" title="MaxOpenConns">MaxOpenConns</a>: <i>Integer</i>
<a href="#authenticationplugin" title="AuthenticationPlugin">AuthenticationPlugin</a>: <i>String</i>
</pre>

## Properties

#### Endpoint

TODO

_Required_: Yes

_Type_: String

_Pattern_: <code>[/@]+([^:/@]+)([:/]+|$)</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Username

TODO

_Required_: Yes

_Type_: String

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Password

TODO

_Required_: No

_Type_: String

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Proxy

TODO

_Required_: No

_Type_: String

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### TLS

_Required_: No

_Type_: String

_Allowed Values_: <code>true</code> | <code>false</code> | <code>skip-verify</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### MaxConnLifetimeSec

_Required_: No

_Type_: Integer

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### MaxOpenConns

_Required_: No

_Type_: Integer

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### AuthenticationPlugin

_Required_: No

_Type_: String

_Allowed Values_: <code>native</code> | <code>cleartext</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

