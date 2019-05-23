---
title: Module securitycenter
aliases:
    - "/reference/pkg/nodejs/@pulumi/azure/securitycenter/"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../">@pulumi/azure</a> &gt; securitycenter

<div class="toggleVisible">
<div class="collapsed">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents">
<ul>
<li><a href="#Contact">class Contact</a></li>
<li><a href="#SubscriptionPricing">class SubscriptionPricing</a></li>
<li><a href="#Workspace">class Workspace</a></li>
<li><a href="#ContactArgs">interface ContactArgs</a></li>
<li><a href="#ContactState">interface ContactState</a></li>
<li><a href="#SubscriptionPricingArgs">interface SubscriptionPricingArgs</a></li>
<li><a href="#SubscriptionPricingState">interface SubscriptionPricingState</a></li>
<li><a href="#WorkspaceArgs">interface WorkspaceArgs</a></li>
<li><a href="#WorkspaceState">interface WorkspaceState</a></li>
</ul>

<a href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts">securitycenter/contact.ts</a> <a href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts">securitycenter/subscriptionPricing.ts</a> <a href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts">securitycenter/workspace.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="Contact">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L26">class <b>Contact</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Manages the subscription's Security Center Contact.

> **NOTE:** Owner access permission is required.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure from "@pulumi/azure";

const example = new azure.securitycenter.Contact("example", {
    alertNotifications: true,
    alertsToAdmins: true,
    email: "contact@example.com",
    phone: "+1-555-555-5555",
});
```

<h3 class="pdoc-member-header" id="Contact-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L54"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Contact(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#ContactArgs'>ContactArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a Contact resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L35">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#ContactState'>ContactState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Contact'>Contact</a></pre>


Get an existing Contact resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-alertNotifications">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L42">property <b>alertNotifications</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>alertNotifications: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</pre>
{{% md %}}

Whether to send security alerts notifications to the security contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-alertsToAdmins">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L46">property <b>alertsToAdmins</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>alertsToAdmins: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</pre>
{{% md %}}

Whether to send security alerts notifications to subscription admins.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-email">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L50">property <b>email</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>email: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The email of the Security Center Contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-phone">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L54">property <b>phone</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>phone: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The phone number of the Security Center Contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Contact-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="SubscriptionPricing">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L25">class <b>SubscriptionPricing</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Manages the Pricing Tier for Azure Security Center in the current subscription.

> **NOTE:** This resource requires the `Owner` permission on the Subscription.

> **NOTE:** Deletion of this resource does not change or reset the pricing tier to `Free`

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure from "@pulumi/azure";

const example = new azure.securitycenter.SubscriptionPricing("example", {
    tier: "Standard",
});
```

<h3 class="pdoc-member-header" id="SubscriptionPricing-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L41"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> SubscriptionPricing(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#SubscriptionPricingArgs'>SubscriptionPricingArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a SubscriptionPricing resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="SubscriptionPricing-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L34">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#SubscriptionPricingState'>SubscriptionPricingState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#SubscriptionPricing'>SubscriptionPricing</a></pre>


Get an existing SubscriptionPricing resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="SubscriptionPricing-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="SubscriptionPricing-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="SubscriptionPricing-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="SubscriptionPricing-tier">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L41">property <b>tier</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>tier: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The pricing tier to use. Possible values are `Free` and `Standard`.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="SubscriptionPricing-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="Workspace">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L36">class <b>Workspace</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Manages the subscription's Security Center Workspace.

> **NOTE:** Owner access permission is required.

> **NOTE:** The subscription's pricing model can not be `Free` for this to have any affect.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure from "@pulumi/azure";

const exampleResourceGroup = new azure.core.ResourceGroup("example", {
    location: "westus",
    name: "tfex-security-workspace",
});
const exampleAnalyticsWorkspace = new azure.operationalinsights.AnalyticsWorkspace("example", {
    location: exampleResourceGroup.location,
    name: "tfex-security-workspace",
    resourceGroupName: exampleResourceGroup.name,
    sku: "PerGB2018",
});
const exampleWorkspace = new azure.securitycenter.Workspace("example", {
    scope: "/subscriptions/00000000-0000-0000-0000-000000000000",
    workspaceId: exampleAnalyticsWorkspace.id,
});
```

<h3 class="pdoc-member-header" id="Workspace-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L56"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Workspace(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#WorkspaceArgs'>WorkspaceArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a Workspace resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L45">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#WorkspaceState'>WorkspaceState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Workspace'>Workspace</a></pre>


Get an existing Workspace resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-scope">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L52">property <b>scope</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>scope: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The scope of VMs to send their security data to the desired workspace, unless overridden by a setting with more specific scope.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Workspace-workspaceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L56">property <b>workspaceId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>workspaceId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ID of the Log Analytics Workspace to save the data in.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="ContactArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L127">interface <b>ContactArgs</b></a>
</h2>
<div class="pdoc-module-contents">

The set of arguments for constructing a Contact resource.

<h3 class="pdoc-member-header" id="ContactArgs-alertNotifications">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L131">property <b>alertNotifications</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>alertNotifications: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</pre>
{{% md %}}

Whether to send security alerts notifications to the security contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ContactArgs-alertsToAdmins">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L135">property <b>alertsToAdmins</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>alertsToAdmins: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</pre>
{{% md %}}

Whether to send security alerts notifications to subscription admins.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ContactArgs-email">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L139">property <b>email</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>email: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The email of the Security Center Contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ContactArgs-phone">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L143">property <b>phone</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>phone: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The phone number of the Security Center Contact.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="ContactState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L105">interface <b>ContactState</b></a>
</h2>
<div class="pdoc-module-contents">

Input properties used for looking up and filtering Contact resources.

<h3 class="pdoc-member-header" id="ContactState-alertNotifications">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L109">property <b>alertNotifications</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>alertNotifications?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</pre>
{{% md %}}

Whether to send security alerts notifications to the security contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ContactState-alertsToAdmins">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L113">property <b>alertsToAdmins</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>alertsToAdmins?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</pre>
{{% md %}}

Whether to send security alerts notifications to subscription admins.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ContactState-email">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L117">property <b>email</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>email?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The email of the Security Center Contact.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ContactState-phone">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/contact.ts#L121">property <b>phone</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>phone?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The phone number of the Security Center Contact.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="SubscriptionPricingArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L87">interface <b>SubscriptionPricingArgs</b></a>
</h2>
<div class="pdoc-module-contents">

The set of arguments for constructing a SubscriptionPricing resource.

<h3 class="pdoc-member-header" id="SubscriptionPricingArgs-tier">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L91">property <b>tier</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>tier: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The pricing tier to use. Possible values are `Free` and `Standard`.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="SubscriptionPricingState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L77">interface <b>SubscriptionPricingState</b></a>
</h2>
<div class="pdoc-module-contents">

Input properties used for looking up and filtering SubscriptionPricing resources.

<h3 class="pdoc-member-header" id="SubscriptionPricingState-tier">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/subscriptionPricing.ts#L81">property <b>tier</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>tier?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The pricing tier to use. Possible values are `Free` and `Standard`.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="WorkspaceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L111">interface <b>WorkspaceArgs</b></a>
</h2>
<div class="pdoc-module-contents">

The set of arguments for constructing a Workspace resource.

<h3 class="pdoc-member-header" id="WorkspaceArgs-scope">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L115">property <b>scope</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>scope: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The scope of VMs to send their security data to the desired workspace, unless overridden by a setting with more specific scope.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="WorkspaceArgs-workspaceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L119">property <b>workspaceId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>workspaceId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ID of the Log Analytics Workspace to save the data in.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="WorkspaceState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L97">interface <b>WorkspaceState</b></a>
</h2>
<div class="pdoc-module-contents">

Input properties used for looking up and filtering Workspace resources.

<h3 class="pdoc-member-header" id="WorkspaceState-scope">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L101">property <b>scope</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>scope?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The scope of VMs to send their security data to the desired workspace, unless overridden by a setting with more specific scope.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="WorkspaceState-workspaceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/9ad002cd8d3c86adcf7430e550cbb381cb2e36c5/sdk/nodejs/securitycenter/workspace.ts#L105">property <b>workspaceId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>workspaceId?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ID of the Log Analytics Workspace to save the data in.

{{% /md %}}
</div>
</div>