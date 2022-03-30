# CLATest

This is a test of the [https://cla-assistant.io/](https://cla-assistant.io/) Github integration. It uses Github auth to digitally sign a pull request prior to merge to ensure that a contributor has signed a contributor licence agreement (CLA). The Licence can be constructed from [https://contributoragreements.org/ca-cla-chooser](https://contributoragreements.org/ca-cla-chooser). The cla-assistant requires the licence is stored as a [GitHub gist](https://gist.github.com/mondus/25564f96827e39f6c2a9a7b894f4f93f) where metadate can be used to capture additional required fields (e.g. Name and email).

Note: This is a suitable mechanism for getting individual contributor agreement signatures but is not suitable for organisations. This requires a "wet paper" copy. There is a good guide on this attached to a few projects. E.g.

 - [List Stat Contributing Guidlines](https://lisp-stat.dev/docs/contributing/)
 - [Oasis Open (Good Description of Entity CLA)](https://www.oasis-open.org/open-projects/cla/)
 - [Google Open Source](https://opensource.google/documentation/reference/cla)
 
## How to try this

Create a fork of the repo. Make a change (ideas: correct my spelling, add a useful link, add a meaningless file). Create PR. Wait for the bot to prompt you to sign the CLA.
