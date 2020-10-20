# MuG::MySQL::Config

An example resource schema demonstrating some basic constructs and validation rules.

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "Type" : "MuG::MySQL::Config",
    "Properties" : {
        "<a href="#name" title="Name">Name</a>" : <i>String</i>,
        "<a href="#description" title="Description">Description</a>" : <i>String</i>,
        "<a href="#secureparameter" title="SecureParameter">SecureParameter</a>" : <i><a href="secureparameter.md">SecureParameter</a></i>,
        "<a href="#parameter" title="Parameter">Parameter</a>" : <i><a href="parameter.md">Parameter</a></i>,
        "<a href="#providerconfiguration" title="ProviderConfiguration">ProviderConfiguration</a>" : <i><a href="providerconfiguration.md">ProviderConfiguration</a></i>,
        "<a href="#vpcconfig" title="VpcConfig">VpcConfig</a>" : <i><a href="vpcconfig.md">VpcConfig</a></i>,
        "<a href="#tags" title="Tags">Tags</a>" : <i>[ <a href="tag.md">Tag</a>, ... ]</i>,
    }
}
</pre>

### YAML

<pre>
Type: MuG::MySQL::Config
Properties:
    <a href="#name" title="Name">Name</a>: <i>String</i>
    <a href="#description" title="Description">Description</a>: <i>String</i>
    <a href="#secureparameter" title="SecureParameter">SecureParameter</a>: <i><a href="secureparameter.md">SecureParameter</a></i>
    <a href="#parameter" title="Parameter">Parameter</a>: <i><a href="parameter.md">Parameter</a></i>
    <a href="#providerconfiguration" title="ProviderConfiguration">ProviderConfiguration</a>: <i><a href="providerconfiguration.md">ProviderConfiguration</a></i>
    <a href="#vpcconfig" title="VpcConfig">VpcConfig</a>: <i><a href="vpcconfig.md">VpcConfig</a></i>
    <a href="#tags" title="Tags">Tags</a>: <i>
      - <a href="tag.md">Tag</a></i>
</pre>

## Properties

#### Name

TODO Description and pattern

_Required_: Yes

_Type_: String

_Update requires_: [Replacement](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-replacement)

#### Description

_Required_: No

_Type_: String

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### SecureParameter

_Required_: No

_Type_: <a href="secureparameter.md">SecureParameter</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Parameter

_Required_: No

_Type_: <a href="parameter.md">Parameter</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### ProviderConfiguration

_Required_: Yes

_Type_: <a href="providerconfiguration.md">ProviderConfiguration</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### VpcConfig

_Required_: No

_Type_: <a href="vpcconfig.md">VpcConfig</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Tags

_Required_: No

_Type_: List of <a href="tag.md">Tag</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

## Return Values

### Ref

When you pass the logical ID of this resource to the intrinsic `Ref` function, Ref returns the Id.

### Fn::GetAtt

The `Fn::GetAtt` intrinsic function returns a value for a specified attribute of this type. The following are the available attributes and sample return values.

For more information about using the `Fn::GetAtt` intrinsic function, see [Fn::GetAtt](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-getatt.html).

#### Id

Returns the <code>Id</code> value.

#### ARN

Returns the <code>ARN</code> value.

#### Version

Returns the <code>Version</code> value.

