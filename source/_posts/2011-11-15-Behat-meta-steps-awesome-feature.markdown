---
layout: page
single: true
---

Hello guys, let me show you how to prepare Behat meta step.

For example, you need start each your scenario form one entry point - logged in as specific user and located at homepage.

<!-- more -->

In this case you will need start each your scenario like this:

{% gist 1371256 myScenario.feature %}

Let`s hide all login steps to meta step.

Add to your FeatureContext

{% gist 1371256 FeatureContext.php %}

now you can use it at your feature definition.

{% gist 1371256 myScenarioImproved.feature %}

Much better now!
