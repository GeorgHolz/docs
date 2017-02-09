
To run an existing test, you have to open the test case or test suite by clicking its name in the repository.
The test case (or test suite) details page will open. On this page you can see all the test steps and for the test suite the containing test case of your test. If you want to execute your test case, click _Run_.

![Test case details](attachments/test-run/testCaseDetails.png)

The _Select Run Configuration_ page will open. On this page, you can set the run configuration for the test case (or test suite) you want to exectue.

![Test Run Configuration](attachments/test-run/runConfiguration.png)

If you have selected a selenium hub from a supported selenium hub provider (TestingBot, SauceLabs or Browserstack), you will get access to the operating system and screen resolution selection.

![Select Run Configuration with OS and resolution selection](attachments/test-run/runConfigurationWithOS.png)

The following options are available:

**Application**

Set the application on which the test will be run.

**Selenium Hub**

Set the Selenium hub on which the test will be executed.

**Browser**

Set the browser in which the test will be run.

**Operating System**

If you have selected a selenium hub from a supported selenium hub provider (TestingBot, SauceLabs or Browserstack), you will get access to the operating system selection. Here you can set the operating system, on which the test case will be run on.

<div class="alert alert-info">

This option is only available for supported Selenium hubs.

</div>

If you want to read more about the different supported operating system, read the [Supported selenium hub provider section](supported-selenium-hub-provider) of this documentation.

**Resolution**

This option is only available, if you have selected a selenium hub from a supported selenium hub provider and a valid operating system. With this option, you can set the screen resolution of the operating system you have selected earlier. The available screen resolutions are the supported resolutions for the operating system given by the selenium hub provider.

<div class="alert alert-info">

This option is only available for supported Selenium hubs.

</div>

If you want to read more about the different supported screen resolutions, read the [Supported selenium hub provider section](supported-selenium-hub-provider) of this documentation.

**Enable Screenshots**

Enable the taking of screenshots during the test run.

**Action Log Depth**

Set the depth of the error logging.

As soon as you have finished setting the run configuration, you can execute the test case by clicking _Run_ or you can schedule the test case by clicking _Schedule_. If you want to know more about scheduling test cases in ATS, visit the [Scheduling section](scheduling).
