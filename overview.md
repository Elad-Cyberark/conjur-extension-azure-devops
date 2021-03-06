This extension provides build and release tasks for packaging and publishing Azure Devops Extensions to the [Visual Studio Marketplace](https://marketplace.visualstudio.com). There are also tasks to share and install your extension to your Azure Devops organisation or Team Foundation Server.

## How to use

After installing the extension, you can add one (or more) of the tasks to a new or existing [build definition](https://www.visualstudio.com/en-us/docs/build/define/create) or [release definition](https://www.visualstudio.com/en-us/docs/release/author-release-definition/more-release-definition)


DO NOT STORE THE CONJUR API KEY IN PLAIN TEXT. Store the conjur api key either in the Azure Key Vault or as a secret variable on the pipeline.


![config-task](config-get-conjur-secret.png)

## Available tasks

Azure DevOps

* **GetConjurSecret**: Retrieve secrets from conjur and set them as pipeline variable secrets

## Get the source

The [source](https://github.com/AndrewCopeland/conjur-extension-azure-devops) for this extension is on GitHub. Take, fork, and extend.

## Contribute

This extension was created by Andrew Copeland.

## Feedback and issues

If you have feedback or issues file an issue on [GitHub](https://github.com/AndrewCopeland/conjur-extension-azure-devops)
