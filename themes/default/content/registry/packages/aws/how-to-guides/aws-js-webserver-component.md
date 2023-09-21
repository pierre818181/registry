---
title: "AWS Web Server Component | JavaScript"
h1: "AWS Web Server Component"
linktitle: "AWS Web Server Component"
meta_desc: "AWS Web Server Component How-to Guide using JavaScript"
no_edit_this_page: true
cloud: aws
language: js
layout: package
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/mktutorial. -->

<p class="mb-4 flex">
    <a class="flex flex-wrap items-center rounded-md font-display text-lg text-white bg-blue-600 border-2 border-blue-600 px-2 mr-2 whitespace-no-wrap hover:text-white" style="height: 45px;" href="https://github.com/pulumi/examples/tree/master/aws-js-webserver-component" target="_blank">
        <span><i class="fab fa-github pr-2"></i> View Code</span>
    </a>
    <a href="https://app.pulumi.com/new?template=https://github.com/pulumi/examples/blob/master/aws-js-webserver-component/README.md" target="_blank">
        <img src="https://get.pulumi.com/new/button.svg" alt="Deploy">
    </a>
</p>


Deploy an EC2 instance with the `@pulumi/aws` package, using a common module for creating an instance. We define a function, `createInstance`, in [webserver.js](https://github.com/pulumi/examples/blob/master/aws-js-webserver-component/webserver.js) and use it in the main program, [index.js](https://github.com/pulumi/examples/blob/master/aws-js-webserver-component/index.js).

For a walkthrough of the main example, see [Simple Web Server Using Amazon EC2](https://www.pulumi.com/docs/tutorials/aws/ec2-webserver/).
