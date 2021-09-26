# Custom templates

A custom template can be used to help streamline the deployment of a container or stack.

{% hint style="info" %}
You can also [create a template from an existing deployed stack](../stacks/template.md).
{% endhint %}

## Viewing the list of custom templates

To view a list of custom templates, from the menu select **App Templates** then select **Custom Templates**.

![](../../../.gitbook/assets/templates-custom-1.gif)

## Creating a new custom template

### Entering the basic information

Click **Add Custom Template** then complete the details, using the table below as a guide.

| Field/Option | Overview |
| :--- | :--- |
| Title | Give the template a descriptive name. |
| Description | Enter a brief description of what your template includes. |
| Note | Note any extra information about the template \(optional\). |
| Icon URL | Enter the URL to an icon to be used for the template when it appears in the list \(optional\). |
| Platform | Select the compatible platform for the template. Options are **Linux** or **Windows**. |
| Type | Select the type of template. Options are **Standalone** or **Swarm**. |

![](../../../.gitbook/assets/templates-custom-2.png)

### Selecting the build method

Next, choose the build method that suits your needs. You can use the web editor to manually enter your docker-compose file, upload a docker-compose.yml file from your local computer, or pull the compose file from a Git repository.

#### Web editor

Paste the contents of your docker-compose file into the box provided. Once all the details have been completed, click **Create custom template**.

![Using the Web editor](../../../.gitbook/assets/templates-custom-3.png)

#### Upload

Click **Select file** to browse for a docker-compose file to upload. Once all the details have been completed, click **Create custom template**.

![Using the Upload method](../../../.gitbook/assets/templates-custom-4.png)

#### Git repository

Fill in the details for your Git repository.

| Field/Option | Overview |
| :--- | :--- |
| Repository URL | Enter the URL to your Git repository. |
| Repository reference | Enter the repository reference to define the branch or tag to pull from. If blank, the default `HEAD` reference will be used. |
| Compose path | Enter the path within the repository to your docker-compose file. |

![Configuring a Git repository](../../../.gitbook/assets/templates-custom-5.png)

If your repository requires access authentication, toggle **Authentication** on then enter the username and password. When all the details have been entered, click **Create custom template**.
